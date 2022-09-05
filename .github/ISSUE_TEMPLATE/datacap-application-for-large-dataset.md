---
name: Large Dataset Notary application
about: Clients should use this application form to request a DataCap allocation via a LDN for a dataset
title: "[DataCap Application] <Organization> - <Project Name>"
labels: 'application, Phase: Diligence'
assignees: ''

---
# Large Dataset Notary Application

To apply for DataCap to onboard your dataset to Filecoin, please fill out the following.

## Core Information
- Organization Name: Solana Lab.
- Website / Social Media: https://solana.com/ (this is for Solana Lab. & Solana Foundation)
- Total amount of DataCap being requested (between 500 TiB and 5 PiB): 3.4 PiB
- Weekly allocation of DataCap requested (usually between 1-100TiB): 50TiB 
- On-chain address for first allocation: f1xw7jxdldohcdu4ec4a5mcnbtvutyjptawojmuzy

_Please respond to the questions below by replacing the text saying "Please answer here". Include as much detail as you can in your answer._

## Project details

Share a brief history of your project and organization.
```
Solana is a public L1 blockchain. 
Here is the official history page: https://docs.solana.com/history
The project is to store solana snapshots it has produced and the snapshots it will produce in Filecoin network.
```

What is the primary source of funding for this project?
```
Solana Lab.
```

What other projects/ecosystem stakeholders is this project associated with?
```
solana ecosystem: https://solana.com/ecosystem
```

## Use-case details

Describe the data being stored onto Filecoin
```
Snapshots are compressed tar archives which store a copy of solana-accounts at a given slot.
Solana warehouse node generates snapshots hourly and in the end of epoch it produces a folder  contains all snapshots of a epoch period.

```
Where was the data in this dataset sourced from?
```
A special kind of solana validator called warehouse node produces snapshots. 
The warehouse node generates snapshots and uploads them to a storage every solana-epoch time.

```

Can you share a sample of the data? A link to a file, an image, a table, etc., are good ways to do this. 
```
If you have aws account. 
https://s3.console.aws.amazon.com/s3/buckets/filecoin-snapshot-test?region=ap-southeast-1&tab=objects
download address:
s3://filecoin-snapshot-test
```
        
Confirm that this is a public dataset that can be retrieved by anyone on the Network (i.e., no specific permissions or access rights are required to view the data).
```
Yes. This is a public dataset.
```

What is the expected retrieval frequency for this data?
```
less than  5 times per month.
```

For how long do you plan to keep this dataset stored on Filecoin?
```
We plan to keep dataset as long as possible unless unavoidable situation. For example, cost of storage is unaffordable.
```


## DataCap allocation plan

In which geographies (countries, regions) do you plan on making storage deals?
```
Diverse regions and countries are prefered. 

```

How will you be distributing your data to storage providers? Is there an offline data transfer process?
```
Prefer online process. 
```
How do you plan on choosing the storage providers with whom you will be making deals? This should include a plan to ensure the data is retrievable in the future both by you and others.
```
We plan to have 5 replicas and plan to find 5 providers. 
```

How will you be distributing deals across storage providers?
```
We are trying possible methods with 2 providers and will find more providers.
```

Do you have the resources/funding to start making deals as soon as you receive DataCap? What support from the community would help you onboard onto Filecoin?
```
Solana Lab. will fund the project to store solana snapshots in Filecoin network.
Onboarding documents have been received from Filecoin experts.

```
