# GridHealth

Connect Claude Code and supported Claude plugin surfaces to GridHealth’s released public healthcare AI catalog, published risk assessments, methodology and supporting evidence. The remote MCP server also provides product dossiers and monitoring-plan drafts.

## Setup

After installing the plugin, authenticate its Grid connection through the client’s MCP controls using an eligible verified work email. The server uses OAuth with published client metadata. No client secret or fixed callback port belongs in this package.

The connector does not access private hospital inventory or patient records, change GridHealth records, or activate monitoring. Text and structured results remain available when interactive Apps are unsupported. Assessments support governance review rather than clinical decision-making.

## Data handling

Full-conversation capture is off. GridHealth retains account, verified work-email, sign-in, usage, quota and security/audit metadata to operate the service. Ordinary telemetry excludes conversation text and MCP tool argument/result bodies. Some account and operational records have no automatic expiry. Operational logs have 30-day retention, and backups have separate retention. This is not a claim that GridHealth stores no data.

## Support

Server: https://mcp.gridhealth.io/mcp
Website: https://www.gridhealth.io
Support: support@gridhealth.io
Privacy: https://www.gridhealth.io/privacy-policy
Terms: https://www.gridhealth.io/terms-of-service

The package’s configuration and documentation are licensed under the MIT license. This license does not cover the remote service, catalog data, assessments, brand names or trademarks; use of the service remains subject to GridHealth’s terms.
