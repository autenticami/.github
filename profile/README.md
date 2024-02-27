# Autenticami

<p align="center">
  <img src="assets/logo/transparent-txt/transparent-txt-2lines.svg" class="center" width="400px" height="auto"/>
</p>

`Autenticami` A Multi-Account and Multi-Tenant Policy-Based Access Control Platform to enable a modern Identity-Based Access Control.

As an `Autenticami administrator` you can create multiple accounts and create multiple projects within each account.

All you have to do is describe your project's `resources` within your account and create your own access control policies. Resources are organized into project's domains.

`Autenticami` allows to specify who or what can access resources by the means of fine-grained permissions:

- `Who`: *Identities (Users and Roles) authenticated in the application*
- `Can Access`: *Permissions granted by attaching policies*
- `Resources`: *Resources targeted by permissions*

To enforce the access control process, the application implements the Policy Enforcement Point using the available SDKs

Below is a sample policy document for granting access to the Employee and Timesheet resources of an HR project (hr-app):

![alt text](assets/vscode/vscode-screenshot.png)
