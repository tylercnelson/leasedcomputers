# leasedcomputers
This repository contains a series of bash scripts designed to compare Active Directory logs against a document containing serial numbers of leased computers from a banking client’s equipment vendor. The output is a document containing hostnames of all leased computers which have logged into the network within the past year. The output can be fed into the next script which pings all of the hostnames to determine their network status. This allowed me to track down the hostnames, branch locations, and network status of all leased computers to be retrieved and replaced with new equipment in order to reduce department leasing costs. The scripts can't be run as-is without accompanying logs which I am unable to include in due to confidentiality.
