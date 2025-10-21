Challenge 3 - Import Set
In your own words, write 3-4 sentences explaining Import sets, transform maps, import set tables, etc.

Import Sets in ServiceNow are used to bring data from external sources (like Excel, CSV, or databases) into ServiceNow.
When data is imported, it first goes into a temporary table called the Import Set Table, which stores the raw data.
Then, a Transform Map is used to map (or connect) the fields from the import set table to the target table in ServiceNow (like the Incident or User table).
Finally, the transformation process moves the data from the import set table to the correct place in the target table safely and accurately.


Challenge 4 - Explain the CSDM
In your own words, write a short essay on the CSDM. You should include: what it is, why its useful, and how it is structured. 2-3 paragraphs is fine.

The CSDM (Common Service Data Model) in ServiceNow is a standard way to organize and connect data in the CMDB. It defines how different parts of a service—like applications, business services, and infrastructure—relate to each other.

It’s useful because it keeps data consistent and helps different ServiceNow apps work together properly. With CSDM, you can easily track how IT services support business operations, which improves reporting, troubleshooting, and decision-making.

CSDM is divided into layers such as Design, Build, Manage, and Consume. Each layer represents a different stage of how a service is planned, created, maintained, and used, making it easier to understand the full picture of IT services.


Challenge 5 - Explain the Security Center & Shared Responsibility Model In your own words, write a short paragraph explaining the purpose of the Security Center and the Shared Responsibility Model.

The Security Center in ServiceNow is a place where you can monitor, manage, and improve the security of your instance. It helps identify potential risks, track compliance, and ensure that security settings are properly configured.

The Shared Responsibility Model explains that both ServiceNow and the customer share the responsibility for security. ServiceNow is responsible for securing the platform itself (infrastructure, network, and application), while customers are responsible for managing their own data, users, and access controls within the platform. This ensures overall safety and compliance from both sides.
