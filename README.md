# workshop Intro
This is the workshop for Calicocloud demo in RedHat Openshift platform, including some common cases for DevOps and security team.

## Join the Slack Channel

[Calico User Group Slack](https://slack.projectcalico.org/) is a great resource to ask any questions about Calico. If you are not a part of this Slack group yet, we highly recommend [joining it](https://slack.projectcalico.org/) to participate in discussions or ask questions. 

[OCP User Group Slack] 

## Workshop objectives

The intent of this workshop is to educate any person working with OCP cluster in one way or another about Calico cloud features and how to use them. While there are many capabilities that Calico provides, this workshop focuses on a subset of those that are used most often by different types of technical users.


## STEP 1 - Order a tigera demo cluster in [RedHat demo system](https://rhpds.redhat.com/catalog/explorer/) 

  - [WIP][OCP: Order a tigera demo cluster](modules/creating-demo-cluster.md)


## STEP 2 - Sign up in Calicocloud  

  - [Calico Cloud trial account](https://www.calicocloud.io/home/)
  - for instructor-led workshop use instructions in the email you receive to request a Calico Trial account
  - for self-paced workshop follow the [link to register](https://www.calicocloud.io/home) for a Calico Trial account

## STEP 3 - Joining your cluster to Calico Cloud

  - [Joining cluster to Calico Cloud](modules/joining-calico-cloud.md)


## STEP 4 - Configure demo applications

  - [Configuring demo applications](modules/configuring-demo-apps.md)

## STEP 5 - Try out some use cases

In this workshop we are going to focus on these main use cases:

- **East-West Controls: App service control & Microsegmentation**
- **North-South Controls: DNS Egress Controls**
- **Observability: Dynamic Service Graph & Kibana dashboard**

## Charpter A - Beginner

- [East-West: controls-App service control](modules/app-service-control.md)
- [East-West: controls-Pod microsegmentation](modules/pod-microsegmentation.md)
- [North-South: Controls-DNS egress control](modules/dns-egress-controls.md)
- [North-South: Controls-Global threadfeed](modules/global-threadfeed.md)

- [Observability: Calico Manager UI](modules/manager-ui.md)
- [Observability: Kibana dashboard](modules/kibana-dashboard.md)
- [Observability: L7 visibility](modules/enable-l7-visibility.md) 

## Charpter B - Intermediate


## STEP 6 - Clean up your test environment

- [clean up](modules/clean-up.md)