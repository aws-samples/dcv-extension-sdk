## NICE DCV Extension SDK

NICE DCV is a high-performance remote display protocol. It lets you securely deliver remote desktops and application streaming from any cloud or data center to any device, over varying network conditions. By using NICE DCV with Amazon EC2, you can run graphics-intensive applications remotely on Amazon EC2 instances. You can then stream the results to more modest client machines, which eliminates the need for expensive dedicated workstations.

With the DCV Extension SDK, developers can integrate DCV protocol with their applications. The following are typical use cases:
- Provide high-level device redirection for custom hardware devices in remote sessions.
- Establish virtual channels between DCV Server and DCV Client to enhance remote application usability.
- Describe the DCV client and DCV server runtime components and allow applications to interact with them.
A DCV extension may communicate with either a DCV client or a DCV server, depending on where it is installed. In addition, the DCV extension could request a virtual channel via the DCV protocol and then use this virtual channel to send arbitrary data.


The NICE DCV Extension SDK uses Protocol Buffers (protobuf), an open-source data format designed to serialize structured data in a compact, binary form. By using Protocol Buffers, DCV components and extensions can communicate with one another in a way that is platform-independent and extensible, regardless of the selected programming language.

This repository contains protobuf definition file `extensions.proto`

To provide feedback, please file an issue.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This project is licensed under the Apache-2.0 License.
