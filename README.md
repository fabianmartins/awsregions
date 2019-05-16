# awsregions

The purpose of this project is to maintain an array of the AWS Regions released, with information of Continent, Name, and Id.

It is expected to be used as a submodule for other projects where an updated list of AWS Regions is required.

An instance of this tuple it would be the following, for the Oregon region (us-west-2).

~~~
{
    "Name": "Oregon",
    "Continent" : "Americas",
    "Id": "us-west-2"
}
~~~

This file is compliant with the region names used at the [AWS Region Table](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/), and I just remove some asteriks when they exist (like in Osaka**).

