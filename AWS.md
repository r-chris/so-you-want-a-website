# Amazon Web Services (AWS)

Amazon is one of the largest providers of (commercial) web services that many companies use for host their "cloud" infrastructure.

## How does it work?

Primarily, you pay Amazon for 2 things (separately):
 * Computers
 * Storage

## Computer Instances (EC2)

You can (flexibly) rent a computer (they call them instances) that will be billed by time.
If you only use the computer for 1 hour, you will only have to pay for that one hour.
The cheapest and smallest computer (at time of writing) is called a t2.nano at $0.0065* per hour:
 * 1 day: $0.156
 * 31 days: $4.836
 * 356 days: $55.536

*Be aware that this is subject to change at any time.

Ok, so you can rent a computer for less than $5 per month.
This isn't a very powerful computer, but it is enough to host a very simple website for a few visitors.

For the first 12 months, AWS actually offers 750 hours / month of free t2.micro (the next "level" up) instance usage: https://aws.amazon.com/free/
Basically, you can run a single instance for free for 12 months.

## Storage (S3)

In addition to computers you can rent long-term storage from Amazon, which is not billed by time, but by amount.
This is **not** the storage on the computer you just rented!
Basically, it's not very different to your Dropbox folder, but you actually have to pay for it ;)

The pricing options are very flexible based on location (!), storage amount and how quickly you want to access the data.
To get you an idea, you might be charged $0.03 / GB / month
 * 5 GB for 1 month: $0.15
 * 5 GB for 12 months: $1.80
 * 1 TB for 1 month: $30.72
 * 1 TB for 12 month: $368.64
 
There are many more costs (data transfer, etc) that I will not detail here, but it certainly puts consumer cloud storage prices into perspective.

In the end you won't need much (or any of this sort of storage) for a small website, so this cost should be negligible or even zero.
