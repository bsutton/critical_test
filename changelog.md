# CHANGELOG

## 1.0.7

the critical test application now returns -1 if any tests failed. Added hidden verbose flag to make diagnostics easier.

## 1.0.6

Fixed a bug caused when a child process is spawned which directly prints to stdout. We now strip this out of the json messages to stop json decode problems.

## 1.0.5

Improvements to the readme.

## 1.0.4

Changed the run\_failed switch to runfailed. spelling in the readme.

## 1.0.3

Minor cleanup on the readme.

## 1.0.2

renamed flag --run\_failed to --runfailed Fixed a counting problem on the error logs when failures and errors occure.

## 1.0.1

Added noojee logo.

## 1.0.0

First release of critical test.
