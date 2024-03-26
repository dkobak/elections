# Polling station data for Russian federal elections

This folder contains raw election data for all Russian federal elections from 2000 onwards. Data scraped by Sergey Shpilkin (until 2021) and by Ivan Shukshin (2024).


## Notes

### Presidential election 2000

91,333 polling stations, 105,635,786 registered voters. There are no polling-station-level data for 104 constituencies (all constituencies in Chechnya and Yakutia, as well as some in other regions) encompassing 2,930,483 registered voters, as well as for all polling stations located outside of the country. Constituency-level data for missing constituencies can be found [here](https://drive.google.com/file/d/0ByFMnUnpIlriYWZpMHdYRXgySXc/view). Together, the sums agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&vrn=10010001189753&type=227).


### Parliamentary election 2003

95,205 polling stations, 108,913,062 registered voters. After excluding 24 stations with zero ballots, there are the following remaining differences with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100095621&vrn=100100095619&region=0&global=1&sub_region=0&prver=0&pronetvd=0&vibid=100100095621&type=233) (108,906,249 registered voters):

* Bashkortostan: 2,932,369 vs. 2,930,413 at izbirkom.ru;
* Moscow Oblast: 5,559,984 vs. 5,558,141 at izbirkom.ru;
* Novosibirsk Oblast: 2,087,163 vs. 2,087,161 at izbirkom.ru. 

This is likely due to election results being later canceled at several polling stations.


### Presidential election 2004

95,779 polling stations, 108,064,342 registered voters. After excluding 2 stations with zero ballots, the sums agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=1001000882951&vrn=1001000882950&region=0&global=1&sub_region=0&prver=0&pronetvd=null&vibid=1001000882951&type=227) (108,064,281 registered voters).


### Parliamentary election 2007

96,193 polling stations, 109,148,196 registered voters. After excluding 11 stations with zero ballots, the sums agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100021960186&vrn=100100021960181&region=0&global=1&sub_region=0&prver=0&pronetvd=null&vibid=100100021960186&type=233) (109,145,517 registered voters).


### Presidential election 2008

96,612 polling stations, 107,222,016 registered voters. The sums agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100022249920&vrn=100100022176412&region=0&global=1&sub_region=0&prver=0&pronetvd=null&vibid=100100022249920&type=227).


### Parliamentary election 2011

95,225 polling stations, 109,229,337 registered voters.  The sums agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100028713304&vrn=100100028713299&region=0&global=1&sub_region=0&prver=0&pronetvd=null&vibid=100100028713304&type=233).


### Presidential election 2012

95,415 polling stations, 109,860,331 registered voters. The sums agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100031793509&vrn=100100031793505&region=0&global=1&sub_region=0&prver=0&pronetvd=null&vibid=100100031793509&type=227).


### Parliamentary election 2016

96,871 polling stations, 110,061,200 registered voters. The sums agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100067795854&vrn=100100067795849&region=0&global=1&sub_region=0&prver=0&pronetvd=0&vibid=100100067795854&type=233).


### Presidential election 2018

97,699 polling stations, 109,008,428 registered voters. Note: the sums do not fully agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=1&tvd=100100084849066&vrn=100100084849062&region=0&global=1&sub_region=0&prver=0&pronetvd=null&vibid=100100084849066&type=227) that lists 109,001,306 registered voters because the results on four polling stations have later been canceled (stations corresponding to rows 45559, 45563, 92554, 92561 in the CSV file, assuming header is row 1).


### Constitutional referendum 2020

96,765 polling stations, 107,999,611 registered voters. The table does not include two pseudo-stations containing results of electronic voting (one in Moscow with 1,051,155 registered voters, and one in Nizhny Novgorod Oblast with 139,571 registered voters). Taking those into account, the sums agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&vrn=100100163596966&type=465) listing 109,190,337 registered voters.


### Parliamentary election 2021

96,325 polling stations, 109,204,662 registered voters. The table contains electorinic voting results as well. The sums agree with [http://www.vybory.izbirkom.ru](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=0&tvd=100100225883177&vrn=100100225883172&region=0&global=&sub_region=0&prver=0&pronetvd=null&vibid=100100225883177&type=233).


### Presidential election 2024

The table contains 94,214 polling stations. 2,268 polling stations in four annexed Ukrainian regions (Донецкая Народная Республика, Запорожская область, Луганская Народная Республика, Херсонская область) do not have any data: polling-station data for these regions have not been released. 7 polling stations collected no ballots and show zero registered voters. Thus the table contains data for 91,939 polling stations with 99,764,974 registered voters. Additionally, `2024-electronic-voting.csv` gives the results of electronic voting, aggregated by region. It has 8,434,406 registered voters.
