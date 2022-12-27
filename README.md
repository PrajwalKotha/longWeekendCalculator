# longWeekendCalculator
### By providing the year,number of consecuitve days as input and list of holidays (in Body), it will give you the longest possible weekend based on the weekends in that year and the consecuitve holidys you are looking for.

### Default year is : 2023 .

#### Sample URL : http://longestweekend.us-e2.cloudhub.io/getLongWeekend/holidays/3/optionals/0/year/2023

#### Sample Request Payload Body: 

`````````````
{
  "calendar": "United States Holiday Calendar",
  "year": 2023,
  "holidays": [
    {
      "name": "Republic Day - Fixed",
      "startDate": "2023-01-26",
      "endDate": "2023-01-26"
    },
    {
      "name": "May Day - Fixed",
      "startDate": "2023-05-01",
      "endDate": "2023-05-01"
    },
    {
      "name": "Telangana Formation Day - Fixed",
      "startDate": "2023-06-02",
      "endDate": "2023-06-02"
    },
    {
      "name": "Bakrid/Id-ul-Zuha/Eidul Azha * - Fixed",
      "startDate": "2023-06-29",
      "endDate": "2023-06-29"
    },
    {
      "name": "Independence Day - Fixed",
      "startDate": "2023-08-15",
      "endDate": "2023-08-15"
    },
    {
      "name": "Mahatma Gandhi Jayanti - Fixed",
      "startDate": "2023-10-02",
      "endDate": "2023-10-02"
    },
    {
      "name": "Vijaya Dasami/ Dussehra / Dasara / Durga Puja Dasami - Fixed",
      "startDate": "2023-10-24",
      "endDate": "2023-10-24"
    },
    {
      "name": "Christmas - Fixed",
      "startDate": "2023-12-25",
      "endDate": "2023-12-25"
    },
    {
      "name": "New Year's Day - Fixed on Weekend",
      "startDate": "2023-01-01",
      "endDate": "2023-01-01"
    },
    {
      "name": "Bhogi - Fixed on Weekend",
      "startDate": "2023-01-14",
      "endDate": "2023-01-14"
    },
    {
      "name": "Maha Shivaratri - Fixed on Weekend",
      "startDate": "2023-02-18",
      "endDate": "2023-02-18"
    },
    {
      "name": "Ramzan-Id /Id-Ul-Fitr */ Khutub-e-Ramzan *  - Fixed on Weekend",
      "startDate": "2023-04-22",
      "endDate": "2023-04-22"
    },
    {
      "name": "Deepavali / Diwali / Kali Puja - Fixed on Weekend",
      "startDate": "2023-11-12",
      "endDate": "2023-11-12"
    },
    {
      "name": "New Year’s Day / Christian New Year Day - OPTIONAL",
      "startDate": "2023-01-01",
      "endDate": "2023-01-01"
    },
    {
      "name": "Guru Govind Singh Jayanti - OPTIONAL",
      "startDate": "2023-01-05",
      "endDate": "2023-01-05"
    },
    {
      "name": "Birthday of Maharshi Guru GokulDas Ji Maharaj - OPTIONAL",
      "startDate": "2023-01-06",
      "endDate": "2023-01-06"
    },
    {
      "name": "Birthday of Swami Vivekananda - OPTIONAL",
      "startDate": "2023-01-12",
      "endDate": "2023-01-12"
    },
    {
      "name": "Lohari Parv - OPTIONAL",
      "startDate": "2023-01-13",
      "endDate": "2023-01-13"
    },
    {
      "name": "Makar Sankranti/Magha/Bihu/Bhogi - OPTIONAL",
      "startDate": "2023-01-14",
      "endDate": "2023-01-14"
    },
    {
      "name": "Pongal / Makar Sankranti / Uttarayana Punyakala/ Makara Sankranti/ Vassi Uttarayan - OPTIONAL",
      "startDate": "2023-01-15",
      "endDate": "2023-01-15"
    },
    {
      "name": "Kanumu / Thiruvalluvar Day - OPTIONAL",
      "startDate": "2023-01-16",
      "endDate": "2023-01-16"
    },
    {
      "name": "Uzhavar Thirunal - OPTIONAL",
      "startDate": "2023-01-17",
      "endDate": "2023-01-17"
    },
    {
      "name": "Shaheedi Diwas/ Martyrdom day of Hemu Kalani - OPTIONAL",
      "startDate": "2023-01-21",
      "endDate": "2023-01-21"
    },
    {
      "name": "Netaji's Birthday - OPTIONAL",
      "startDate": "2023-01-23",
      "endDate": "2023-01-23"
    },
    {
      "name": "Day before Saraswati Puja - OPTIONAL",
      "startDate": "2023-01-25",
      "endDate": "2023-01-25"
    },
    {
      "name": "Dev Narayan Jayanti - OPTIONAL",
      "startDate": "2023-01-27",
      "endDate": "2023-01-27"
    },
    {
      "name": "Devnarayan Jayanti / Narmada Jayanti - OPTIONAL",
      "startDate": "2023-01-28",
      "endDate": "2023-01-28"
    },
    {
      "name": "Urs of Hazrat Khwaja Moinuddin Chishti Ajmeri Garib Nawaz Rehman - OPTIONAL",
      "startDate": "2023-01-29",
      "endDate": "2023-01-29"
    },
    {
      "name": "Shri MadvaNavami - OPTIONAL",
      "startDate": "2023-01-30",
      "endDate": "2023-01-30"
    },
    {
      "name": "Vishwakarma Jayanti / Hazarat Ali’s Birthday - OPTIONAL",
      "startDate": "2023-02-03",
      "endDate": "2023-02-03"
    },
    {
      "name": "Swami Ramcharan Jayanti /  Birthday of Swami Ramcharan ji Maharaj  - OPTIONAL",
      "startDate": "2023-02-04",
      "endDate": "2023-02-04"
    },
    {
      "name": "Thai Poosam / Hazarat Ali’s Birthday, Guru Ravidas’s Birthday/ Hazrat Ali Jayanti / Sant Ravidas Jayanti / Saint Shiromani Ravidasji's Birthday / Birthday of Hazarat Ali (R.A) - OPTIONAL",
      "startDate": "2023-02-05",
      "endDate": "2023-02-05"
    },
    {
      "name": "Birthday of Dhani Matang Dev - OPTIONAL",
      "startDate": "2023-02-08",
      "endDate": "2023-02-08"
    },
    {
      "name": "Birth Day of Thakur Panchanan Barma - OPTIONAL",
      "startDate": "2023-02-14",
      "endDate": "2023-02-14"
    },
    {
      "name": "Birthday of Swami Dayananda Saraswati / Maharshi Dayanand Saraswati Jayanti - OPTIONAL",
      "startDate": "2023-02-15",
      "endDate": "2023-02-15"
    },
    {
      "name": "Maha Shivratri / Shivaratri / Eklavya Jayanti - OPTIONAL",
      "startDate": "2023-02-18",
      "endDate": "2023-02-18"
    },
    {
      "name": "Shiva ji Jayanti / Chhatrapati Shivaji Maharaj Jayanti / Shab-E-Meraj - OPTIONAL",
      "startDate": "2023-02-19",
      "endDate": "2023-02-19"
    },
    {
      "name": "Gadge Maharaj Jayanti - OPTIONAL",
      "startDate": "2023-02-23",
      "endDate": "2023-02-23"
    },
    {
      "name": "Shabari Jayanti - OPTIONAL",
      "startDate": "2023-02-24",
      "endDate": "2023-02-24"
    },
    {
      "name": "Holika Dahan - OPTIONAL",
      "startDate": "2023-03-06",
      "endDate": "2023-03-06"
    },
    {
      "name": "Holi/ Holika Dahan, Dolyatra /  Shab-E-Barath* - OPTIONAL",
      "startDate": "2023-03-07",
      "endDate": "2023-03-07"
    },
    {
      "name": "Holi Festival / Holi (Day after Doljatra) / Shab-e-Barat - OPTIONAL",
      "startDate": "2023-03-08",
      "endDate": "2023-03-08"
    },
    {
      "name": "Holi / Bhai Duj  - OPTIONAL",
      "startDate": "2023-03-09",
      "endDate": "2023-03-09"
    },
    {
      "name": "Bhakt Mata Karma Jayanti - OPTIONAL",
      "startDate": "2023-03-18",
      "endDate": "2023-03-18"
    },
    {
      "name": "Birth Day of Shri Shri Harichand Thakur (Madhu Krishna Troyodashi Tithi) - OPTIONAL",
      "startDate": "2023-03-19",
      "endDate": "2023-03-19"
    },
    {
      "name": "Virangana Avantibai ka Balidan Diwas - OPTIONAL",
      "startDate": "2023-03-20",
      "endDate": "2023-03-20"
    },
    {
      "name": "Jamshedi Navroz (Parsi Shahenshahi & Parsi Kadmi) - OPTIONAL",
      "startDate": "2023-03-21",
      "endDate": "2023-03-21"
    },
    {
      "name": "Telugu New Year's Day /Ugadi Festival / Chaitra Sukladi/ Gudi Padava /Ugadi/ Cheti Chand / Gudhi Padwa / Gudi Padvo - OPTIONAL",
      "startDate": "2023-03-22",
      "endDate": "2023-03-22"
    },
    {
      "name": "Shaheedi Diwas/ Martyrdom day of Bhagat Singh , Rajguru & Sukhdev / Cheti Chand - OPTIONAL",
      "startDate": "2023-03-23",
      "endDate": "2023-03-23"
    },
    {
      "name": "Devara Dasimayya Jayanti / Maharshi Kayshap Jayanti /NishadRaj Jayanti - OPTIONAL",
      "startDate": "2023-03-26",
      "endDate": "2023-03-26"
    },
    {
      "name": "Chhath Puja - OPTIONAL",
      "startDate": "2023-03-27",
      "endDate": "2023-03-27"
    },
    {
      "name": "Sri Rama Navami - OPTIONAL",
      "startDate": "2023-03-30",
      "endDate": "2023-03-30"
    },
    {
      "name": " Mahavir Jayanti - OPTIONAL",
      "startDate": "2023-04-03",
      "endDate": "2023-04-03"
    },
    {
      "name": "Mahaveer Jayanthi / Mahavir Janma Kalyanak - OPTIONAL",
      "startDate": "2023-04-04",
      "endDate": "2023-04-04"
    },
    {
      "name": "Hatkeshvar Jayanti / Maharishi Kashyap and Maharaja Nishadraj Guha Jayanti / Babu Jagjivan Ram's Birthday - OPTIONAL",
      "startDate": "2023-04-05",
      "endDate": "2023-04-05"
    },
    {
      "name": "Hanuman Jayanti / Pesah (1st Day)(Yahudi) - OPTIONAL",
      "startDate": "2023-04-06",
      "endDate": "2023-04-06"
    },
    {
      "name": "Good Friday - OPTIONAL",
      "startDate": "2023-04-07",
      "endDate": "2023-04-07"
    },
    {
      "name": "Holy Satruday / Easter Saturday - OPTIONAL",
      "startDate": "2023-04-08",
      "endDate": "2023-04-08"
    },
    {
      "name": "Easter Sunday - OPTIONAL",
      "startDate": "2023-04-09",
      "endDate": "2023-04-09"
    },
    {
      "name": "Easter Monday - OPTIONAL",
      "startDate": "2023-04-10",
      "endDate": "2023-04-10"
    },
    {
      "name": "Mahatma Jyotiba Phule Jayanti / Shahadat HZT Ali (RA) - OPTIONAL",
      "startDate": "2023-04-11",
      "endDate": "2023-04-11"
    },
    {
      "name": "Shahdat Hazrath Ali (R.A.) - OPTIONAL",
      "startDate": "2023-04-13",
      "endDate": "2023-04-13"
    },
    {
      "name": "Dr. Baba Saheb (B.R.) Ambedkar's Birthday /Dr. B.R. Ambedkar Jayanti / Vaisakhi /Souramana Ugadi / Vishu / Meshadi / Tamil New year /Jumuatul Wada - OPTIONAL",
      "startDate": "2023-04-14",
      "endDate": "2023-04-14"
    },
    {
      "name": "Bengali New Year's Day (Nababarsha)/ Vaisakhadi /Bahag Bihu - OPTIONAL",
      "startDate": "2023-04-15",
      "endDate": "2023-04-15"
    },
    {
      "name": "Maha Prabhuji's Praktyotsava (Vallabhacharya Jayanit) - OPTIONAL",
      "startDate": "2023-04-16",
      "endDate": "2023-04-16"
    },
    {
      "name": "Chandrashekhar Jayanti / Sain Jayanti - OPTIONAL",
      "startDate": "2023-04-17",
      "endDate": "2023-04-17"
    },
    {
      "name": "Shab-E-Qader - OPTIONAL",
      "startDate": "2023-04-18",
      "endDate": "2023-04-18"
    },
    {
      "name": "Day before Eid-UI-Fitr - OPTIONAL",
      "startDate": "2023-04-20",
      "endDate": "2023-04-20"
    },
    {
      "name": "Jumat-Ul-Wida /Day before Eid-UI-Fitr/ Jamat Ul-Vida / Goodbye Last Friday of Ramadan - OPTIONAL",
      "startDate": "2023-04-21",
      "endDate": "2023-04-21"
    },
    {
      "name": "Parshuram Jayanti / Ramzan-Id /Id-Ul-Fitr */ Khutub-e-Ramzan * / akshaya tritiya - OPTIONAL",
      "startDate": "2023-04-22",
      "endDate": "2023-04-22"
    },
    {
      "name": "Basava Jayanthi/  Ramjan-Id (Id-Ul-Fitra)/ Following day of Ramzan / Zarthost-no-Disho (Parsi Shahenshahi)  - OPTIONAL",
      "startDate": "2023-04-23",
      "endDate": "2023-04-23"
    },
    {
      "name": "Shree Adhya Jagadguru Shankaracharya Jayanti / Sri Shankracharya Jayanti/ Sri Ramanujachrya Jayanti - OPTIONAL",
      "startDate": "2023-04-25",
      "endDate": "2023-04-25"
    },
    {
      "name": "Buddha Purnima / Buddha Pournima / Birth Day of Pandit Raghunath Murmu - OPTIONAL",
      "startDate": "2023-05-05",
      "endDate": "2023-05-05"
    },
    {
      "name": "Birthday of Guru Rabindranath Tagore / Loknayak Maharana Pratap Jayanti - OPTIONAL",
      "startDate": "2023-05-09",
      "endDate": "2023-05-09"
    },
    {
      "name": "kevat Jayanti - OPTIONAL",
      "startDate": "2023-05-15",
      "endDate": "2023-05-15"
    },
    {
      "name": "Maharana Pratap Jayanti / Chhatrasal Jayanti - OPTIONAL",
      "startDate": "2023-05-22",
      "endDate": "2023-05-22"
    },
    {
      "name": "Guru Arjan Dev's Martyrdom Day / Zarthost-no-Disho (Parsi Shahenshahi) - OPTIONAL",
      "startDate": "2023-05-23",
      "endDate": "2023-05-23"
    },
    {
      "name": "Shavuoth (Yahudi) - OPTIONAL",
      "startDate": "2023-05-26",
      "endDate": "2023-05-26"
    },
    {
      "name": "Mahesh Jayanti - OPTIONAL",
      "startDate": "2023-05-29",
      "endDate": "2023-05-29"
    },
    {
      "name": "Guru Arjundev's Martyrdom Day - OPTIONAL",
      "startDate": "2023-05-30",
      "endDate": "2023-05-30"
    },
    {
      "name": "Sant Kabir Jayanti - OPTIONAL",
      "startDate": "2023-06-04",
      "endDate": "2023-06-04"
    },
    {
      "name": "Birsa Munda Shahidi Diwas - OPTIONAL",
      "startDate": "2023-06-09",
      "endDate": "2023-06-09"
    },
    {
      "name": "Rath Yatra / Rathayatra - OPTIONAL",
      "startDate": "2023-06-20",
      "endDate": "2023-06-20"
    },
    {
      "name": "Veerangana Durgavati ka Balidan Diwas - OPTIONAL",
      "startDate": "2023-06-24",
      "endDate": "2023-06-24"
    },
    {
      "name": "Eid-Ul-Adha (Edujjuha ke theek Purva ka Diwas)  - OPTIONAL",
      "startDate": "2023-06-27",
      "endDate": "2023-06-27"
    },
    {
      "name": "Bakri Id (Id-Uz-Zuha) - OPTIONAL",
      "startDate": "2023-06-28",
      "endDate": "2023-06-28"
    },
    {
      "name": "Hul Diwas / Eid-ul-Juha Bakrid - OPTIONAL",
      "startDate": "2023-06-30",
      "endDate": "2023-06-30"
    },
    {
      "name": "Guru Purnima - OPTIONAL",
      "startDate": "2023-07-03",
      "endDate": "2023-07-03"
    },
    {
      "name": "Gadeer-a-Khum - OPTIONAL",
      "startDate": "2023-07-06",
      "endDate": "2023-07-06"
    },
    {
      "name": "EID_E Ghadeer - OPTIONAL",
      "startDate": "2023-07-07",
      "endDate": "2023-07-07"
    },
    {
      "name": "Birth Day of Poet Bhanu Bhakt (for Darjeeling & Kalimpong District only). - OPTIONAL",
      "startDate": "2023-07-13",
      "endDate": "2023-07-13"
    },
    {
      "name": "Gatha Gahamber (Parsi Kadi) - OPTIONAL",
      "startDate": "2023-07-14",
      "endDate": "2023-07-14"
    },
    {
      "name": "Parsi New Year Day Eve (Parsi Kadmi) - OPTIONAL",
      "startDate": "2023-07-16",
      "endDate": "2023-07-16"
    },
    {
      "name": "Parsi New Year Day (Parsi Kadmi) / Bonalu - OPTIONAL",
      "startDate": "2023-07-17",
      "endDate": "2023-07-17"
    },
    {
      "name": "Khordad Sal (Parsi Kadmi) - OPTIONAL",
      "startDate": "2023-07-22",
      "endDate": "2023-07-22"
    },
    {
      "name": "Yom-a-Ashura - OPTIONAL",
      "startDate": "2023-07-27",
      "endDate": "2023-07-27"
    },
    {
      "name": "Tisha-be-aav (Yahudi) / 9th Moharram - OPTIONAL",
      "startDate": "2023-07-28",
      "endDate": "2023-07-28"
    },
    {
      "name": "Last day of Muharram* / Muharram* / Moharum / Moharam (Tajiya)(By Moon) / Shahadat Imam Hussian (R.A) 10th Moharam - OPTIONAL",
      "startDate": "2023-07-29",
      "endDate": "2023-07-29"
    },
    {
      "name": "Muharram - OPTIONAL",
      "startDate": "2023-07-30",
      "endDate": "2023-07-30"
    },
    {
      "name": "Shaheed Udham Singh Martyrdom Day - OPTIONAL",
      "startDate": "2023-07-31",
      "endDate": "2023-07-31"
    },
    {
      "name": "Balram Jayanti - OPTIONAL",
      "startDate": "2023-08-05",
      "endDate": "2023-08-05"
    },
    {
      "name": "International Tribal Day  / International day of the world's indigenous people - OPTIONAL",
      "startDate": "2023-08-09",
      "endDate": "2023-08-09"
    },
    {
      "name": "Gatha Gahamber (Parsh Shahenshahi) / Durgadas Rathore Jayanti - OPTIONAL",
      "startDate": "2023-08-13",
      "endDate": "2023-08-13"
    },
    {
      "name": "Parsi New Year’s day/ Nauraj / Parsi New Year (Shahenshahi) - OPTIONAL",
      "startDate": "2023-08-16",
      "endDate": "2023-08-16"
    },
    {
      "name": "Hariyali Teej - OPTIONAL",
      "startDate": "2023-08-19",
      "endDate": "2023-08-19"
    },
    {
      "name": "Vinayaka Chaturthi - OPTIONAL",
      "startDate": "2023-08-20",
      "endDate": "2023-08-20"
    },
    {
      "name": "Khordad Sal (Parsi Shahenshahi) / Nagpanchami - OPTIONAL",
      "startDate": "2023-08-21",
      "endDate": "2023-08-21"
    },
    {
      "name": "Goswami Tulsidas Jayanti - OPTIONAL",
      "startDate": "2023-08-23",
      "endDate": "2023-08-23"
    },
    {
      "name": "Varalakshmi Vratham / Varamahalakshmi Vratha - OPTIONAL",
      "startDate": "2023-08-25",
      "endDate": "2023-08-25"
    },
    {
      "name": "Rug Upakarma / Onam Festival / Onam or Thiru Onam Day - OPTIONAL",
      "startDate": "2023-08-29",
      "endDate": "2023-08-29"
    },
    {
      "name": "Raksha Bandhan/ Yajur Upakarma - OPTIONAL",
      "startDate": "2023-08-30",
      "endDate": "2023-08-30"
    },
    {
      "name": "Raksha Bandhan / Sravana Purnima / Rakhi Purnima /Brahma Shri Narayan Guruji Jayanthi - OPTIONAL",
      "startDate": "2023-08-31",
      "endDate": "2023-08-31"
    },
    {
      "name": "Kali Muhuruth - OPTIONAL",
      "startDate": "2023-09-03",
      "endDate": "2023-09-03"
    },
    {
      "name": "Krishna Jayanthi / Janmashtami (Smarta) / Sri Krishna Janmashtami / Chehlum / Arbayeen / Thadadi - OPTIONAL",
      "startDate": "2023-09-06",
      "endDate": "2023-09-06"
    },
    {
      "name": "Janmashtami / Sri Krishna Janmashtami / Sri Krishna Astami / Janmashtami (Vaishnva) - OPTIONAL",
      "startDate": "2023-09-07",
      "endDate": "2023-09-07"
    },
    {
      "name": "Next day of Janmashtami / Nand Utsav / Kanya Mariyamma Jayanti - OPTIONAL",
      "startDate": "2023-09-08",
      "endDate": "2023-09-08"
    },
    {
      "name": "Shravan Vad-12 - OPTIONAL",
      "startDate": "2023-09-12",
      "endDate": "2023-09-12"
    },
    {
      "name": "Shravan Vad-13 - OPTIONAL",
      "startDate": "2023-09-13",
      "endDate": "2023-09-13"
    },
    {
      "name": "Shahadat-e-Imam Husan - OPTIONAL",
      "startDate": "2023-09-14",
      "endDate": "2023-09-14"
    },
    {
      "name": "Mahavir Swami Janma Vachan /  Rosh Hashanah - OPTIONAL",
      "startDate": "2023-09-16",
      "endDate": "2023-09-16"
    },
    {
      "name": "Vishwakarma Jayanthi / Vishwakarma Pooja / Vinayaka Chaturthi - OPTIONAL",
      "startDate": "2023-09-17",
      "endDate": "2023-09-17"
    },
    {
      "name": "Swarnagowri Vratham / Vinayaka Chavithi / Varasiddhi Vinayaka Vrata/ Raja Shanker Shah tatha Ragunath Shah ka Balidan Diwas - OPTIONAL",
      "startDate": "2023-09-18",
      "endDate": "2023-09-18"
    },
    {
      "name": "Ganesh Chaturthi / Samvatsari (Chaturthi Paksha) - OPTIONAL",
      "startDate": "2023-09-19",
      "endDate": "2023-09-19"
    },
    {
      "name": "Samwatsari - OPTIONAL",
      "startDate": "2023-09-20",
      "endDate": "2023-09-20"
    },
    {
      "name": "Navakhai - OPTIONAL",
      "startDate": "2023-09-22",
      "endDate": "2023-09-22"
    },
    {
      "name": "Shaheedi Divas/ Haryana War  Heroes' Martyrdom Day - OPTIONAL",
      "startDate": "2023-09-23",
      "endDate": "2023-09-23"
    },
    {
      "name": "Eve to Kippur (Yahudi) - OPTIONAL",
      "startDate": "2023-09-24",
      "endDate": "2023-09-24"
    },
    {
      "name": "Yom Kippur (Yahudi); / Ramdev Jayanti, Teja Dashmi & Khejarli Shahid Day / Dol Gyaras - OPTIONAL",
      "startDate": "2023-09-25",
      "endDate": "2023-09-25"
    },
    {
      "name": "Anant Chaturdashi / Ananta Padmanabha Vrata / Milad-un-Nabi or Id-e Milad (Birthday of Prophet Mohammad) / Milad-un-Nabi / Id-E-Milad / Eid-Milad / EID / Fateha-Dwaz-Daham Miladun Nabi / Barawafat (By Moon) - OPTIONAL",
      "startDate": "2023-09-28",
      "endDate": "2023-09-28"
    },
    {
      "name": "Succoth (Yahudi) - OPTIONAL",
      "startDate": "2023-09-30",
      "endDate": "2023-09-30"
    },
    {
      "name": "Id-e-Maulud (Muslim Shiya) - OPTIONAL",
      "startDate": "2023-10-03",
      "endDate": "2023-10-03"
    },
    {
      "name": "World Mental Health Day - OPTIONAL",
      "startDate": "2023-10-10",
      "endDate": "2023-10-10"
    },
    {
      "name": "Pran Nath Jayanti - OPTIONAL",
      "startDate": "2023-10-13",
      "endDate": "2023-10-13"
    },
    {
      "name": "Mahalaya Amavasya / Bathukamma Starting Day / Sarvpitra Moksha Amawashya - OPTIONAL",
      "startDate": "2023-10-14",
      "endDate": "2023-10-14"
    },
    {
      "name": "Maharaja Agrasen Jayanti / Navratra Sthapana & Maharaja Agrasen Jayanti - OPTIONAL",
      "startDate": "2023-10-15",
      "endDate": "2023-10-15"
    },
    {
      "name": "Tula Sankramana / Durga Puja, Maha Chaturthi - OPTIONAL",
      "startDate": "2023-10-18",
      "endDate": "2023-10-18"
    },
    {
      "name": "Durga Puja, Maha Panchami - OPTIONAL",
      "startDate": "2023-10-19",
      "endDate": "2023-10-19"
    },
    {
      "name": "Durga Puja, Maha Shashthi - OPTIONAL",
      "startDate": "2023-10-20",
      "endDate": "2023-10-20"
    },
    {
      "name": "Dussehra (Saptami) / Durga Puja, Maha Saptami - OPTIONAL",
      "startDate": "2023-10-21",
      "endDate": "2023-10-21"
    },
    {
      "name": "Dussehra (Mahashtami) / Durga Puja Maha Ashtami / Durgashtami - OPTIONAL",
      "startDate": "2023-10-22",
      "endDate": "2023-10-22"
    },
    {
      "name": "Ayudha Pooja / Dussehra (Mahanavmi) / Durga Puja, Maha Nabami / Maharnavami /  - OPTIONAL",
      "startDate": "2023-10-23",
      "endDate": "2023-10-23"
    },
    {
      "name": "Additional Day for Durga Puja / Next day of Vijay Dasami - OPTIONAL",
      "startDate": "2023-10-25",
      "endDate": "2023-10-25"
    },
    {
      "name": "Additional Day for Durga Puja - OPTIONAL",
      "startDate": "2023-10-26",
      "endDate": "2023-10-26"
    },
    {
      "name": "Additional Day for Durga Puja / Yaz Dahum Shareef - OPTIONAL",
      "startDate": "2023-10-27",
      "endDate": "2023-10-27"
    },
    {
      "name": "Maharshi Valmiki Jayanthi / Lakshmi Puja / Maharaj Ajmod Dev Jayanti/ Tekchand Ji Maharaj ka Samadhi - OPTIONAL",
      "startDate": "2023-10-28",
      "endDate": "2023-10-28"
    },
    {
      "name": "Sardar Vallabhbhai Patel's Birthday / Sardar Vallabhbhai Patel and  Acharya Narendra Dev Jayanti - OPTIONAL",
      "startDate": "2023-10-31",
      "endDate": "2023-10-31"
    },
    {
      "name": "Karaka Chaturthi (Karva Chouth) - OPTIONAL",
      "startDate": "2023-11-01",
      "endDate": "2023-11-01"
    },
    {
      "name": "Dr. Saiyyadna Sahab ka Janm Diwas  - OPTIONAL",
      "startDate": "2023-11-03",
      "endDate": "2023-11-03"
    },
    {
      "name": "Dhan Terash - OPTIONAL",
      "startDate": "2023-11-10",
      "endDate": "2023-11-10"
    },
    {
      "name": "Kali Chaudash / Naraka Chaturdhi / Dipawali (Dakshin Bhartiya) - OPTIONAL",
      "startDate": "2023-11-11",
      "endDate": "2023-11-11"
    },
    {
      "name": "Diwali (Deepavali) / Diwali Amavasya (Laxmi Pujan)/ Naraka Chaturdashi / Kali Puja - OPTIONAL",
      "startDate": "2023-11-12",
      "endDate": "2023-11-12"
    },
    {
      "name": "Govardhan Puja / Vishvakarma Day / Additional Day for Kali Puja / Second day of Deepavali - OPTIONAL",
      "startDate": "2023-11-13",
      "endDate": "2023-11-13"
    },
    {
      "name": "Balipadyami, Deepavali / Additional Day for Kali Puja / Diwali (Bali Pratipada) / Vikram Samvant New Year Day - OPTIONAL",
      "startDate": "2023-11-14",
      "endDate": "2023-11-14"
    },
    {
      "name": "Bhai Duj / Chitragupta Jayanti/ Bhaubeej / Bhratridwitiya /Birth Day of Birsa Munda / Janjatiya Gaurav Divas - OPTIONAL",
      "startDate": "2023-11-15",
      "endDate": "2023-11-15"
    },
    {
      "name": "Day after Bhratridwitiya / Uda Devi Martyr’s Day - OPTIONAL",
      "startDate": "2023-11-16",
      "endDate": "2023-11-16"
    },
    {
      "name": "Chhat Puja - OPTIONAL",
      "startDate": "2023-11-18",
      "endDate": "2023-11-18"
    },
    {
      "name": "Chhat Puja / Pratihar Shashthi or Surya Shashthi (Chhat Puja) / Bhagwan Shahastrabahu Jayanti  - OPTIONAL",
      "startDate": "2023-11-19",
      "endDate": "2023-11-19"
    },
    {
      "name": "Additional Day for Chhat Puja - OPTIONAL",
      "startDate": "2023-11-20",
      "endDate": "2023-11-20"
    },
    {
      "name": "Jhalkari Jayanti  - OPTIONAL",
      "startDate": "2023-11-22",
      "endDate": "2023-11-22"
    },
    {
      "name": "Namdeva Jayanti  - OPTIONAL",
      "startDate": "2023-11-23",
      "endDate": "2023-11-23"
    },
    {
      "name": "Guru Teg Bahadur’s Martyrdom Day - OPTIONAL",
      "startDate": "2023-11-24",
      "endDate": "2023-11-24"
    },
    {
      "name": "Guru Nanak Dev's birthday/ Guru Nanak Jayanthi / Kartik Purnima/ Kartak Sud-15 (Dev-Diwali) - OPTIONAL",
      "startDate": "2023-11-27",
      "endDate": "2023-11-27"
    },
    {
      "name": "Huttari Festival / Huthri Festival - OPTIONAL",
      "startDate": "2023-11-28",
      "endDate": "2023-11-28"
    },
    {
      "name": "Birthday of HZT Syed Mohammed Juvanpuri Mahdi Ma'ud (A.S) - OPTIONAL",
      "startDate": "2023-11-29",
      "endDate": "2023-11-29"
    },
    {
      "name": "Kanakadasa Jayanti - OPTIONAL",
      "startDate": "2023-11-30",
      "endDate": "2023-11-30"
    },
    {
      "name": "International Day of Disabled Persons - OPTIONAL",
      "startDate": "2023-12-03",
      "endDate": "2023-12-03"
    },
    {
      "name": "Kranti SuryaTantya Bhil Balidan Diwas - OPTIONAL",
      "startDate": "2023-12-04",
      "endDate": "2023-12-04"
    },
    {
      "name": "Guru Ghasidas Jayanti - OPTIONAL",
      "startDate": "2023-12-18",
      "endDate": "2023-12-18"
    },
    {
      "name": "Sant Shri Jintaran Taran Jayanti - OPTIONAL",
      "startDate": "2023-12-19",
      "endDate": "2023-12-19"
    },
    {
      "name": "Shrimad Bhagwad Gita Jayanti - OPTIONAL",
      "startDate": "2023-12-22",
      "endDate": "2023-12-22"
    },
    {
      "name": "Chaudhary Charan Singh’s birthday - OPTIONAL",
      "startDate": "2023-12-23",
      "endDate": "2023-12-23"
    },
    {
      "name": "Christmas Eve  - OPTIONAL",
      "startDate": "2023-12-24",
      "endDate": "2023-12-24"
    },
    {
      "name": "Shaheed Udham Singh's Jayanti/ Boxing Day / Duttatrey Jayanti - OPTIONAL",
      "startDate": "2023-12-26",
      "endDate": "2023-12-26"
    },
    {
      "name": "Balinath Ji Bairwa Jayanti  - OPTIONAL",
      "startDate": "2023-12-31",
      "endDate": "2023-12-31"
    }
  ]
}
``````````````
### If you are using get, the default calendar is used - 2023

#### Default response Body

```````
[
  {
    "2023-04-02": [
      {
        "name": "Weekend Sun",
        "Date": "2023-04-02",
        "Day": "Sun"
      },
      {
        "name": " Mahavir Jayanti - OPTIONAL",
        "Date": "2023-04-03",
        "Day": "Mon"
      },
      {
        "name": "Mahaveer Jayanthi / Mahavir Janma Kalyanak - OPTIONAL",
        "Date": "2023-04-04",
        "Day": "Tue"
      },
      {
        "name": "Hatkeshvar Jayanti / Maharishi Kashyap and Maharaja Nishadraj Guha Jayanti / Babu Jagjivan Ram's Birthday - OPTIONAL",
        "Date": "2023-04-05",
        "Day": "Wed"
      },
      {
        "name": "Hanuman Jayanti / Pesah (1st Day)(Yahudi) - OPTIONAL",
        "Date": "2023-04-06",
        "Day": "Thu"
      },
      {
        "name": "Good Friday - OPTIONAL",
        "Date": "2023-04-07",
        "Day": "Fri"
      },
      {
        "name": "Holy Satruday / Easter Saturday - OPTIONAL",
        "Date": "2023-04-08",
        "Day": "Sat"
      },
      {
        "name": "Easter Sunday - OPTIONAL",
        "Date": "2023-04-09",
        "Day": "Sun"
      },
      {
        "name": "Easter Monday - OPTIONAL",
        "Date": "2023-04-10",
        "Day": "Mon"
      },
      {
        "name": "Mahatma Jyotiba Phule Jayanti / Shahadat HZT Ali (RA) - OPTIONAL",
        "Date": "2023-04-11",
        "Day": "Tue"
      }
    ],
    "consecutiveDays": 10
  },
  {
    "2023-10-20": [
      {
        "name": "Durga Puja, Maha Shashthi - OPTIONAL",
        "Date": "2023-10-20",
        "Day": "Fri"
      },
      {
        "name": "Dussehra (Saptami) / Durga Puja, Maha Saptami - OPTIONAL",
        "Date": "2023-10-21",
        "Day": "Sat"
      },
      {
        "name": "Dussehra (Mahashtami) / Durga Puja Maha Ashtami / Durgashtami - OPTIONAL",
        "Date": "2023-10-22",
        "Day": "Sun"
      },
      {
        "name": "Ayudha Pooja / Dussehra (Mahanavmi) / Durga Puja, Maha Nabami / Maharnavami /  - OPTIONAL",
        "Date": "2023-10-23",
        "Day": "Mon"
      },
      {
        "name": "Vijaya Dasami/ Dussehra / Dasara / Durga Puja Dasami - Fixed",
        "Date": "2023-10-24",
        "Day": "Tue"
      },
      {
        "name": "Additional Day for Durga Puja / Next day of Vijay Dasami - OPTIONAL",
        "Date": "2023-10-25",
        "Day": "Wed"
      },
      {
        "name": "Additional Day for Durga Puja - OPTIONAL",
        "Date": "2023-10-26",
        "Day": "Thu"
      },
      {
        "name": "Additional Day for Durga Puja / Yaz Dahum Shareef - OPTIONAL",
        "Date": "2023-10-27",
        "Day": "Fri"
      },
      {
        "name": "Maharshi Valmiki Jayanthi / Lakshmi Puja / Maharaj Ajmod Dev Jayanti/ Tekchand Ji Maharaj ka Samadhi - OPTIONAL",
        "Date": "2023-10-28",
        "Day": "Sat"
      },
      {
        "name": "Weekend Sun",
        "Date": "2023-10-29",
        "Day": "Sun"
      }
    ],
    "consecutiveDays": 10
  }
]
