---
  title: Replace Galaxkey for evalautors
  description: An introduction into replacing Galaxkey in the service, starting
    with the evaluators journey
  date: 2024-11-05
  # screenshots:
  #   items:
  #     - text: "Emails bcc example 01"
  #       src: emails-bcc-example-01.png
  #     - text: "Emails bcc example 02"
  #       src: emails-bcc-example-02.png
  #     - text: "Emails list view"
  #       src: emails-list-view.png
  #     - text: "Emails message example 01"
  #       src: emails-message-example-01.png
  #     - text: "Emails message example 02.png"
  #       src: emails-message-example-02.png.png
---

## What is Galaxkey?
[GalaxKey Email Encryption](https://www.galaxkey.com/secure-emails/) is used in the case (procurement) management system to enable Procurement to send and receive sensitive and confidential documents to and from educational establishments.

School buying professionals and evaluators use GalaxKey in the tender evaluation and contract handover sections of a procurement.

## Problems with Galaxkey
Procurement operations have told us they provide a lot of support to users during Galaxkey tasks in addition to it being a paid service.

Problems include:
- Having to provide technical support with account creation, two factor authentication, access and more
- Doubling of work, email via Galaxkey and regular email channels
- Inability to focus on procurement due to support requests

## How we plan to remove Galaxkey
As a given procurement can have many evaluators but only usually one or two school buyers we decided to focus on updating the evaluator journey first, as this will have the biggest impact and deliver the most value in time savings.

We will then apply what we have learned and built to deliver a journey to handle the contact handover task with the least amount of effort.


### The Evaluator process
Evaluators are one time users of the service, by this we mean that they use the service to complete a single task over a short timespan, as opposed to school buying professional who use the service frequently over a number of months.

A simplified description of the evaluation journey can be described as:
1. Evaluator receives email telling them to log into Galaxkey
2. Evaluator goes to Galaxkey, signs up for an account, sets up two factor authentication and signs in
3. Evaluator downloads evaluation documents
4. Evaluator completes a declaration of interest form (to report and mitigate any conflict of interests with suppliers)
5. Evaluator does the evaluation as an offline process
6. Evaluator uses Galaxkey to return the completed documents
7. Procurement operations check the documents as 100% complete

### What we want to change
We want to remove Galaxkey as soon as possible, so we plan to focus on only replacing the sending and receiving of files. We will rely on existing manual processes to fill the gaps in the new journey, then return to them once we have completed the contract handover journey.

With this in mind, we plan to get:
1. procurement operations to upload the evaluation packs to the service
2. procurement operations to specify the evaluators email address
3. the service to email evaluators so that they can log in to their “portal”
4. evaluators to download the documents
5. evaluators to upload the completed documents

### Constraints
Beside the aforementioned limits on effort and time to deliver an alternative we also had to consider:
- **A sign in mechanism**
After a technical discussion we decided to use DfE sign in as a way for evaluators to confirm their identity. This combined with procurement operations adding their email addresses means that we know that they own a given email and which procurement to show.

- **A way to upload and download files per evaluator**
We only want evaluators to upload on document set and then the service to duplicate and send them to each evaluator

In addition, we also wanted to start introducing the idea of a task list as in Alpha that was the mechanism that was tested to enable school users to complete procurement tasks. We think that there should be a shared task list for evaluators and schools where some tasks may be visible to both types of user. This will be an opportunity to start examining this concept.

### The design iteration
View the Lucid board to see the proposed journey and how it moved from procurement operations tasks to the evaluators and back again.
[View the journey in Lucid Spark](https://lucid.app/lucidspark/7c72e65d-781d-44d7-a3fe-50988f51ca2c/view)


