# Artifact Appendix

Paper title: **Automatic Generation of Web Censorship Probe Lists**

Artifacts HotCRP Id: **#16**

Requested Badge: **Available**

## Description
Our system finds 119,255 URLs, which we probe for censorship. We thus provide the dataset (i.e. the list of URLs) in this artifact.

### Security/Privacy Issues and Ethical Concerns
As the URLs in this list are intented to be probed for potential censorship in
various locations around the world, some pages may contain content related to
censored topics.

Thus, they may contain adult content, politically sensitive content, or other
potentially sensitive content (such as material relating to
alcohol, drugs, or gambling).

## Basic Requirements
N/A

### Hardware Requirements
N/A

### Software Requirements
N/A

### Estimated Time and Storage Consumption
N/A

## Environment
N/A

### Accessibility
https://github.com/nc2y/probelist/tree/pets24submission

### Set up the environment
N/A

### Testing the Environment
N/A

## Artifact Evaluation

### Main Results and Claims
This is the list of 119,255 URLs that we test for potential censorship in our
paper. In other words, we attempt to access these pages from various global
vantage points to test if there are indications that these pages are censored.
The results of these tests can be found in Section 5.

#### Main Result 1:
From 50 repeated measurements over five months, over 1400 unique domains from
our probe list (of the 119K URLs) were consistently inaccessible via curl on
our servers in various locations in Asia.

#### Main Result 2:
We further verify our curl results through testing with OONI Probe
(https://ooni.org/), a known censorship measurement tool. Of the inaccessible
domains within China in our probe list, over 1000 domains returned anomalies in
the OONI Probe measurements, indicating potential censorship. This was further
validated by testing these domains directly against the Great Firewall's
filters.

### Experiments
N/A

## Limitations
N/A

## Notes on Reusability
We aim for this dataset of potentially blocked sites to be available and used
in a similar manner to other testlists (such as the Citizen Lab testlists
https://github.com/citizenlab/test-lists) to test for censorship worldwide. We
intend to update the URLs at regular intervals, as we aim to integrate the page
generation process with ICLab.
