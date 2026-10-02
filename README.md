# SAP_CPI_Integration_Patterns
Reference implementations of SAP Cloud Integration (SAP Integration Suite) iFlows demonstrating message routing, transformation, splitting and aggregation, encoding, and adapter-based connectivity.

#SAPIntegrationSuite #SAPCPI #CloudIntegration #iFlow #SAPBTP #EnterpriseIntegrationPatterns #MessageTransformation #SAPAdapters #IntegrationAdapters #Connectors #SAPConnectors #OData #SOAP #RESTAPI #XSLT #GroovyScript #MessageMapping #ContentModifier #APIIntegration #Middleware

# SAP Cloud Integration: Integration Patterns

## Overview
This repository contains integration flows (iFlows) built on SAP Cloud
Integration, a capability of SAP Integration Suite on SAP BTP. Each iFlow
demonstrates a specific integration pattern or platform capability, with
sample payloads and configuration notes.

## Scope
- **Message transformation:** Content Modifier, Message Mapping, XSLT,
  Encoder/Decoder
- **Routing and flow control:** Router, Multicast, Splitter,
  Join and Gather
- **Connectivity:** Sender and receiver adapters (HTTP, SOAP, OData, and others)
- **Data handling:** Header, property, and body manipulation; XML and
  non-XML payload processing

## Repository Structure
Each folder is one self-contained scenario:

- `iflow/`: exported integration flow
- `payloads/`: sample input and expected output
- `README.md`: scenario description, components used, and configuration notes

## Prerequisites
- SAP Integration Suite tenant with Cloud Integration enabled
- Required security material and endpoints must be configured separately,
  as credentials are not included in this repository

## Usage
Import the iFlow into an integration package, configure the externalized
parameters, deploy, and test using the sample payloads.
