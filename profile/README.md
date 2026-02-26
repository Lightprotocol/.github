<p align="center">
  <img width="120" src="https://raw.githubusercontent.com/Lightprotocol/light-protocol/main/assets/logo.svg" alt="Light Protocol">
</p>
<h3 align="center">The rent-free Account and Token Standard on Solana</h3>
<p align="center">Built for high performance DeFi, Stablecoin Payments, Agentic Finance, and more.</p>

<br>

<p align="center">
  <a href="https://github.com/Lightprotocol/skills">Agent Skills</a>
  &nbsp;·&nbsp;
  <a href="https://www.zkcompression.com">Documentation</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Lightprotocol/examples-light-token">Examples</a>
    &nbsp;·&nbsp;
    <a href="https://github.com/Lightprotocol/light-protocol">Repository</a>
</p>

<p align="center">
  <a href="https://deepwiki.com/Lightprotocol/light-protocol"><img src="https://deepwiki.com/badge.svg" alt="DeepWiki"></a>
  &nbsp;
  <a href="https://github.com/Lightprotocol/skills"><img src="https://img.shields.io/badge/Agent%20Skills-Compatible-green.svg" alt="Agent Skills"></a>
  &nbsp;
  <a href="https://discord.com/invite/WDAAaX6je2"><img src="https://img.shields.io/discord/992616840251584633?label=Discord&style=flat-square&color=5a66f6" alt="Discord"></a>
  &nbsp;
  <a href="https://twitter.com/lightprotocol"><img src="https://img.shields.io/badge/Twitter-Follow_us-1d9bf0.svg?style=flat-square" alt="Twitter"></a>
</p>

---

## Documentation and Examples

Light Protocol builds scalable infrastructure on Solana:
* **ZK Compression** is a Solana account primitive that lets you create tokens and PDAs without rent-exemption on Solana, built with Helius. 
* The **Light Token Program** is a high-performance token standard that is functionally equivalent to SPL and build on ZK Compression. The Light Token SDK keeps code changes minimal and is a superset of the SPL-token API.

> [Documentation](https://www.zkcompression.com) | [Examples](https://github.com/Lightprotocol/examples-light-token)
## Agent Skills


Install or view how to integrate with claude code, cursor, openclaw, or any agent here: [Lightprotocol/skills](https://github.com/Lightprotocol/skills)

```bash
npx skills add Lightprotocol/skills
```

> Find dedicated [prompts for agents here](prompts).


## CLI

Run this single command to install the CLI.

```bash
npm i -g @lightprotocol/zk-compression-cli
```
> [Documentation](https://www.zkcompression.com/resources/cli-installation) | [Source](https://github.com/Lightprotocol/light-protocol/tree/main/cli)

## SDK Reference

#### Client SDK

<table>
<colgroup><col width="40%"><col width="60%"></colgroup>
<tr><td><a href="https://lightprotocol.github.io/light-protocol/stateless.js/index.html">@lightprotocol/stateless.js</a></td><td>RPC client for Light Token and ZK Compression</td></tr>
<tr><td><a href="https://lightprotocol.github.io/light-protocol/compressed-token/index.html">@lightprotocol/compressed-token</a></td><td>Light Token Operations</td></tr>
<tr><td><a href="https://docs.rs/light-client/latest/light_client/">light-client</a></td><td>RPC client for Light Token and ZK Compression</td></tr>
<tr><td><a href="https://docs.rs/light-token-client/latest/light_token_client/">light-token-client</a></td><td>Light Token Operations</td></tr>
</table>

#### Program SDK for Anchor & Native Rust

<table>
<colgroup><col width="40%"><col width="60%"></colgroup>
<tr><td><a href="https://docs.rs/light-sdk/latest/light_sdk/">light-sdk</a></td><td>Core SDK for on-chain programs</td></tr>
<tr><td><a href="https://docs.rs/light-token/latest/light_token/">light-token</a></td><td>CPI instructions for Light Token program</td></tr>
<tr><td><a href="https://docs.rs/light-account/latest/light_account/">light-account</a></td><td>Light Accounts and Light Token Accounts</td></tr>
</table>


#### Program SDK for Pinocchio

<table>
<colgroup><col width="40%"><col width="60%"></colgroup>
<tr><td><a href="https://docs.rs/light-sdk-pinocchio/latest/light_sdk_pinocchio/">light-sdk-pinocchio</a></td><td>Core SDK for Pinocchio programs</td></tr>
<tr><td><a href="https://docs.rs/light-token-pinocchio/latest/light_token_pinocchio/">light-token-pinocchio</a></td><td>CPI instructions for Light Token program</td></tr>
<tr><td><a href="https://docs.rs/light-account-pinocchio/latest/light_account_pinocchio/">light-account-pinocchio</a></td><td>Light Accounts and Light Token Accounts</td></tr>
</table>

#### Testing

<table>
<colgroup><col width="40%"><col width="60%"></colgroup>
<tr><td><a href="https://docs.rs/crate/light-program-test/latest">light-program-test</a></td><td>Local testing framework for Anchor and Pinocchio programs</td></tr>
</table>

#### Other

<table>
<colgroup><col width="40%"><col width="60%"></colgroup>
<tr><td><a href="https://www.npmjs.com/package/@lightprotocol/nullifier-program">@lightprotocol/nullifier-program</a></td><td>Client for nullifier to prevent on-chain instructions from being executed twice</td></tr>
</table>

## Security

The Light protocol on-chain programs were audited by independent security firms, such as Certora, OtterSec, Accretion, HashCloak, Neodyme, and Zellic. See reports [here](https://github.com/Lightprotocol/light-protocol/blob/main/audits).

The ZK Compression circuit was formally verified by Reilabs. See the report [here](https://github.com/Lightprotocol/light-protocol/blob/main/audits/reilabs_2024-08_circuits_formal_verification_report.pdf).
Information about the Trusted Setup Ceremony for the groth16 circuits is [here](https://github.com/Lightprotocol/gnark-mt-setup/blob/main/README.md).
