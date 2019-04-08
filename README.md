# FlexSearch
FlexSearch Module for Filemaker

## Overview

A portable search bar object that performs 2 key functions, 1) a regular quickfind on the designated quickfind fields, and 2) a "FlexSearch" which is like a quickfind but also matches the middles and ends of words, and acts much like a "*" wildcard character.

## Where to Start

Read the Modules -> FlexSearch -> FlexSearch READ ME script. Go to http://www.modularfilemaker.org/ to learn more about modules.

## Version 2.0.0 features

- ability to filter searches with
- json parameters
- no longer depends on Hyperlist module
- use merge field to define flex search fields instead of global variables
- Submodule `FlexSearch: Find: Public` can allow users to build custom find workflows that suit any find logic they want. This can be used outside of flexsearch too! NOTE: read script header for customization made for use in this module.
