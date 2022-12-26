# longWeekendCalculator
### By providing the year,number of consecuitve days as input and list of holidays (in Body), it will give you the longest possible weekend based on the weekends in that year and the consecuitve holidys you are looking for.

### Default year is : 2019 .

#### Sample URL : http://localhost:8081/getLongHoliday/year/2019/length/3

#### Sample Payload Body: 

`````````````
{
  "calendar": "United States Holiday Calendar",
  "year": 2019,
  "holidays": [
    {
      "name": "New Year's Day",
      "startDate": "2019-01-01",
      "endDate": "2019-01-02"
    },
    {
      "name": "Martin Luther King Jr's Birthday",
      "startDate": "2019-01-21",
      "endDate": "2019-01-21"
    },
    {
      "name": "Memorial Day",
      "startDate": "2019-05-27",
      "endDate": "2019-05-27"
    },
    {
      "name": "Summer Shutdown",
      "startDate": "2019-07-01",
      "endDate": "2019-07-01"
    },
    {
      "name": "Summer Shutdown",
      "startDate": "2019-07-02",
      "endDate": "2019-07-02"
    },
    {
      "name": "Summer Shutdown",
      "startDate": "2019-07-03",
      "endDate": "2019-07-03"
    },
    {
      "name": "Independence Day",
      "startDate": "2019-07-04",
      "endDate": "2019-07-04"
    },
    {
      "name": "Summer Shutdown",
      "startDate": "2019-07-05",
      "endDate": "2019-07-05"
    },
    {
      "name": "Labor Day",
      "startDate": "2019-09-02",
      "endDate": "2019-09-02"
    },
    {
      "name": "Thanksgiving Day",
      "startDate": "2019-11-28",
      "endDate": "2019-11-28"
    },
    {
      "name": "Day after Thanksgiving",
      "startDate": "2019-11-29",
      "endDate": "2019-11-29"
    },
    {
      "name": "Winter Shutdown",
      "startDate": "2019-12-23",
      "endDate": "2019-12-23"
    },
    {
      "name": "Winter Shutdown",
      "startDate": "2019-12-24",
      "endDate": "2019-12-24"
    },
    {
      "name": "Christmas Day",
      "startDate": "2019-12-25",
      "endDate": "2019-12-25"
    },
    {
      "name": "Winter Shutdown",
      "startDate": "2019-12-26",
      "endDate": "2019-12-26"
    },
    {
      "name": "Winter Shutdown",
      "startDate": "2019-12-27",
      "endDate": "2019-12-27"
    },
    {
      "name": "Winter Shutdown",
      "startDate": "2019-12-30",
      "endDate": "2019-12-30"
    },
    {
      "name": "Winter Shutdown",
      "startDate": "2019-12-31",
      "endDate": "2019-12-31"
    }
  ]
}
