# Unix Epochalypse

The Unix Epochalypse (or the Year 2038 problem) is the day clocks on a number of systems will flip from January 19, 2038 3:14:08 AM UTC to December 13, 1901 8:45:52 PM UTC. This is because of the use of a 32-bit signed integer for the current seconds since midnight UTC on January 1, 1970, the Unix epoch. Values only from -2,147,483,648 to 2,147,483,647 are stored. When finally reaching the limit, it’ll be the seconds before the epoch starting at the lowest supported integer.

