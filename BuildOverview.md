# Build Overview

Whenever you want to inspect a specific build in a configuration, first thing
you will see is the __Build Row__. 

## Build Row

<img src="Images/build_row.png">

Each __Build Row__ represents a single build in the build configuration. It contains
following information:

* Project/build configuration :checkered_flag: 
* Branch :checkered_flag: 
* Number :checkered_flag: 
* Favorite :checkered_flag: 
* Personal :checkered_flag: 
* State :checkered_flag: 
    * Running
    * Finished
    * Canceled
    * Failed to start
* Status :checkered_flag: 
    * Successful
    * Failed
* Pin/tags :checkered_flag: 
* Artifacts :checkered_flag: 
* Agent :checkered_flag: 
    * Agent Pool
* Dependencies (chain icon) :checkered_flag: 
* Comment :checkered_flag: 

## Expanded Build Row

You can click on the free space anywhere in the __Build Row__ and it will expand.

<img src="Images/expanded_build_row.png">

The __Expanded Build Row__ adds more details about the build:

* Timeline :oncoming_automobile: 
* Build log tail :oncoming_automobile: 
* Extensions :oncoming_automobile: 
	* Code coverage
    * Install in Toolbox
* X build problems :oncoming_automobile: 
* Tests counters :checkered_flag: 
* X failed test :checkered_flag: 
* X latest changes (ordered by time) :checkered_flag: 
	* In the code
	* In the configuration
* Snapshot dependencies overview :checkered_flag: 
* Deployments :oncoming_automobile: 


##Build Overview Page

For in-depth information, you can open the __Build Overview Page_.

<img src="Images/build_overview.png">


### Tabs 

<img height="66" width="670" src="Images/build_overview_tabs.png">

* Overview  :checkered_flag: 
    * Build info
    * Build details
* Tests :oncoming_automobile:
    * Filters
        * By name
        * By status
    * Timeline
  	* List/tree
* Build log :oncoming_automobile:
    * Timeline
    * Flame chart
* Snapshot dependencies :oncoming_automobile:

### Build Timeline

<img height="117" width="623" src="Images/build_overview_timeline.png">

* Build steps :oncoming_automobile:
* Clickable error :oncoming_automobile: 

[//]: <> ( ## Build Log)

### Changes

<img height="149" width="426" src="Images/build_overview_changes.png">

* X latest changes (ordered by time) :checkered_flag: 
    * In the code
    * In the configuration

### Tests

* Counters :oncoming_automobile: 
* Failed test line :oncoming_automobile: 


[//]: <> ( ### Other Builds)
