# How to Assess Measurement Capabilities of a Security Monitoring Infrastructure and Plan Investment through a Graph-based Approach

## Abstract

Security monitoring is a crucial activity in managing cybersecurity for any organization, as it plays a foundational role in various security processes and systems, such as risk identification and threat detection.
To be effective, security monitoring is currently implemented by orchestrating multiple data sources to provide corrective actions promptly.
Poor monitoring management can compromise an organization's cybersecurity posture and waste resources.
This issue is further exacerbated by the fact that monitoring infrastructures are typically managed with a limited resource budget.
This paper addresses the problem of supporting security experts in managing security infrastructures efficiently and effectively by considering the trade-off cost-benefit between using specific monitoring tools and the benefit of including them in the organization's infrastructure.
To this aim, we introduce a graph-based model named Metric Graph Model (MGM) to represent dependencies between security metrics and the monitoring infrastructure. It is used to solve a set of security monitoring problems: (i) Metrics Computability, to assess the measurement capabilities of the monitoring infrastructure, (ii) Instrument Redundancy, to assess the utility of the instruments used for the monitoring, and (iii) Cost-Bounded Constraint, to identify the optimal monitoring infrastructure in terms of cost-benefit trade-off.
We prove the NP-hardness of some of these problems, propose heuristics for solving them based on the Metric Graph Model and provide an experimental evaluation that shows their better performance than existing solutions. Finally, we present a usage scenario based on an instance of the Metric Graph Model derived from a state-of-the-art security metric taxonomy currently employed by organizations.
It demonstrates how the proposed approach supports an administrator in optimizing the security monitoring infrastructure in terms of saving resources and speeding up the decision-making process.

## Getting Started

To get started with the MGM project, you'll first need to install the required dependencies and then run the web application. Follow the steps below to set up the project on your local machine.

### Prerequisites

Before you can run the project, make sure you have Python installed on your system. This project has been tested on Python 3.8 and above. You can download Python from [the official website](https://www.python.org/downloads/).

### Installing Dependencies

1. Navigate to the project directory: cd Metric-Management-Graph
2. Install the required Python dependencies: pip install -r requirements.txt

This will start the web application on your local machine. You can access it by visiting `http://localhost:5000` in your web browser.

## Contributing

Contributions to the MGM project are welcome. If you wish to contribute, please fork the repository and submit a pull request.

## Cite this work

TBD
