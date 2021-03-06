Input sample:

Your program should accept a path to a filename as its first argument. Each line of the file contains a list of time periods separated by a semicolon and a single space. Each time period is represented as the begin date and the end date. Each date consists of a month as an abbreviated name and a year with century as a decimal number separated by a single space. The begin date and the end date are separated by a hyphen.

For example:


Feb 2004-Dec 2009; Sep 2004-Jul 2008
Aug 2013-Mar 2014; Apr 2013-Aug 2013; Jun 2014-Aug 2015; Apr 2003-Nov 2004; Apr 2014-Jan 2015
Mar 2003-Jul 2003; Nov 2003-Jan 2004; Apr 1999-Nov 1999
Apr 1992-Dec 1993; Feb 1996-Sep 1997; Jan 2002-Jun 2002; Sep 2003-Apr 2004; Feb 2010-Nov 2011
Feb 2004-May 2004; Jun 2004-Jul 2004

Output sample:

Print out the actual work experience in years for each test case.

For example:

5
4
1
6
0

Constraints:

    The number of lines in a file is in a range from 20 to 40.
    The dates are in a range from Jan 1990 to Dec 2020.
    The end date is greater than the begin date.
    The begin date is the first day of a given month, and the end date is the last day of a given month.
