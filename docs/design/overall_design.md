#KBase Genome Browser

##Introduction

This document will serve as a design specification for the KBase genome browser module.

The genome browser will likely be composed of 3 parts:  

1. Front end UI - users will interact with this part to view a range genomic data in some specific context.
2. Data access layer - Regardless of what the data store is, there will need to be some access layer between it and the front end. This layer should fetch and manage data retrieved from the datastore for rendering.
3. Data store - Genome information needs to be available in a data storage module of some sort. This might be the Workspace service as it stands, or the Central Store, or something new. But it'll be a necessary component of the browser.

## Front end requirements

## Data access layer requirements

## Data store requirements