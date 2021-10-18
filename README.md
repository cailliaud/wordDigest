# Digest Word

## Specifications

Our application goal is to expose multiple API to transform text for our customers.

### Use Cases

* A blank text is not supported, an error should be return to the user
* Vowels should be replaced by a pipe '|'
* A counter of the number of vowels transformed should be exposed with the transformed text.

## Technical Requirements

* Application should run with Java 11
* Rest API exposed with Spring Boot
