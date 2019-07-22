# xChecklist (Cross-cutting feature checklists)
It's not trivial to consider Cross cutting features during product development. This repository contains checklists for several well-known cross-cutting features we want to consider during liferay products development. Development covers not only coding but also design and product definition phases.

This [foundational document](https://docs.google.com/document/d/1dtrH85YP-TNhcjEQnS7XcJNt0t0IfkfepK0xvoxLjgk/edit#) explains the essentials of this initiative and the rationale of this repository. In addition, this is the list of [cross-cutting features or product traits](https://airtable.com/tbl1H8pBchOLT9doA/viwgHASgx2xOm6g8l?blocks=hide) we'd like to cover.

## Repository structure
This is work in progress, so expect some changes in the structure.

To foster collaboration and separation of concerns, checklists are organized as follows:

    xcutting/          → a top-level folder for each cross cutting feature 
       readme.md       → description of the xcutting feature. Scope, what it covers and what not. Owner team (if any)
       version.txt     → current version of this checklist    
       functional/     → items targeted to functional feature analysis    
          must/        → items here must be considered to minimally include xcutting feature from a functional perspective  
             item-A.md → checklist item (or group of them). Use item name as filename
             item-B.md → checklist item (or group of them). Use item name as filename
          should/      → items here have to be considered to appropriately cover the xcutting feature from a functional perspective (same structure as must/)             
       technical/      → items targeted to feature implementation (same structure as functional/)
