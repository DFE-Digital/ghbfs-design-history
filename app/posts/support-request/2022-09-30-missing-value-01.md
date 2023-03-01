---
  title: Cases are missing their value
  description: How do we make sure cases have a value without affecting the user journey
  date: 2022-09-30
  screenshots:
    items:
      - text: "Value alternative"
        src: value-alternative.png
      - text: "Value as is"
        src: value-as-is.png
      - text: "Value iteration"
        src: value-iteration.png
      - text: "Value stats 01"
        src: value-stats-01.png
---

## What we changed
- Removed the option to say it's not about procurement
- Removed the option to not provide a value
- Value field is not mandatory but likewise not labelled as optional

## Why we changed this
We know that around half of cases that proc ops deal with don't have a value associated to the case when the support request is submitted. There are only a small number of cases where the case is not about procurement so how do we make sure that users that have a procurement are providing a value.

We debated on whether this is mandatory or whether there are other ways to make sure the information is filled in. We know that not offering a clear way for users to move past the question is not ideal but we also know that the value of a case is important to proc ops and to the project to understand whether we are saving money for schools. We took the decision to make sure that we tracked the metrics on this change.

## How it works
The value field is optional but it is not labelled as mandatory or optional as assume users will think they need to fill it in. The question can still be skipped but we assume this will not be as clear to the user.

## Further considerations
We are tracking Google Analtyics dropoff rates on the value page.
We are also tracking the percentage of cases that proc ops receive that have a value.
We will know it is a success if the drop off rate is the same or less and that the percentage of cases with a value supplied is increased.
A value we would consider is a realistic value and not for instance £1, or £2222