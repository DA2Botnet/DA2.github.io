# Distributed-Automation

## Summary 

This set of applications is for a system made of up hosts connected to a centralized system for automation purposes. 
This contains the libraries and the basic framework. 

This botnet isn't a traditional style one. This isn't desgined to run on host located all around the world.
It is designed to virtualize thousands of hosts distributem them all around the globe and run tasks.

This botnet is not designed to be hidden on a computer. Disguising the traffic running between hosts and applications is not a priority. However, disguising outbound traffic heading to external destations does need to be distributed to between many differnet vpns. The name "Distributed Automation" comes from the fact that:
1. Bots will be <b>distributed</b> between different external IP addresses using VPN Gateways. See: [VPN Gateway](https://github.com/DA2Botnet/VPN-Obfuscator-Appliance) for more details
2. Tasks will be <b>distributed</b> to these bots to run a different times throughout a set period (usually 24hrs). 
3. The bots run time will be <b>distributed</b> throught 24 hour intervals
4. All of the trafic comes from many different virtualized hosts <b>distributed</b>
5. This has some <b>distribution</b>/decentralization where different node groups (called franchises)

<I>Please Use Ethically</I>

## Definitions

> - <b>Framework:</b> Structure for the botnet and the base plugins run on top
> - <b>Plugin:</b> The applications that run on top of the bots in the botnet
> - <b>Franchise:</b> A subsystem node that can be functionally independent. 
## Folder Structure

- [Director Appliance](https://github.com/DA2Botnet/Director-Appliance)
  - [Application Source](https://github.com/DA2Botnet/Director-Source)
  - [Interface Console](https://github.com/DA2Botnet/Interface-Console)
- [Scheduler Appliance](https://github.com/DA2Botnet/Scheduler-Appliance)
  - [Application Source](https://github.com/DA2Botnet/Scheduler-Source)
- [Query Generator Appliance](https://github.com/DA2Botnet/QueryGenerator-Appliance)
  - [Application Source](https://github.com/DA2Botnet/QueryGenerator-Source)
  - [Docker Image](https://github.com/DA2Botnet/QueryGenerator-Docker)
  - [Public API](https://github.com/DA2Botnet/QueryGenerator-User-API)
- [Generic Appliance Scripts](https://github.com/DA2Botnet/Generic-Appliance-Scripts)
- [DA2 Libraries](https://github.com/DA2Botnet/DA2-Libraries)
- [BW Libraries](https://github.com/DA2Botnet/BW-Libraries)

## Instructions

Please see [deployment guide](https://github.com/DA2Botnet/Docs/blob/main/deployment/deployment_guide.md) for detailed instructions
