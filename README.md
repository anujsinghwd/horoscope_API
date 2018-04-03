# horoscope_API

# API Usage

  - features
    - Daily Horoscope)
    - Weekly Horoscope
    - Monthly Horoscope
    - Yearly Horoscope

### Daily Horoscope Request Format
 
#### GET: `https://raashiphal.herokuapp.com?type=today&&sunsign=<sunsign>`
```json
{
  "horoscope": "It is a good day to renew old acquaintances and make new relationships. Your friends and relatives will probably visit you today. A jovial feeling will pervade your home. You may throw a grand party for your guests, says Ganesha.",
  "date": "April 03, 2018 04:22:52 PM",
  "SunSign": "leo"
}
```


### Weekly Horoscope Request Format
 
#### GET: `https://raashiphal.herokuapp.com?type=week&&sunsign=<sunsign>`
```json
{
    "horoscope": "There is some trouble brewing in your family for some time now. Sadly, you haven’t had the time to look into it. Well, says Ganesha, you better do so now. Listen to your loved ones and do whatever you can to recoup the lost harmony. Sun, the ruler of your Sign, is exalted and is transiting through the 9th House with retrograde Mercury for company. On the other hand, Venus is in Taurus in the 10th House. Both these planetary positions spell success for businessmen. You may come across an amazing deal. However, retrograde Mercury may play a spoilsport, and you may not be able to finalize the deal. Be patient; when the right time comes, nothing would be able to stop you from succeeding in this regard. On the job front, restlessness may bog you down. But what is going to help you handle anything and everything shall be your fit mind and body. So, you must know that where your priorities should lie!",
    "date": "April 03, 2018 05:17:00 PM",
    "SunSign": "leo"
}
```



### Monthly Horoscope Request Format
 
#### GET: `https://raashiphal.herokuapp.com?type=month&&sunsign=<sunsign>`
```json
{
    "horoscope": "The month may look tough and challenging as it begins but gradually shall become easy to handle. There is some trouble brewing on the personal front for quite some time now. And you are being blamed of neglecting the family matters. Pay heed before it gets too late. Listen to your loved ones and attend to their needs and requirements at this juncture. Being the core family member, you are the one expected to lend maximum emotional support. And troughs and crests at the home front shall continue for the rest of the month, but you, being a Lion can surely take care of it, provided you put your royal ego aside and give importance to the relationship. Sun, the ruler of your Sign is exalted and is transiting through the 9th House with retrograde Mercury for the company. On the other hand, Venus is in Taurus in the 10th House. Both these planetary positions spell success for businessmen. You may a lucrative business opportunity, but as Mercury is retrograde, you may not be able to clinch it. However, don’t lose heart. Minor gains are indicated in the weeks to come. If you are in a job, you shall have to put in extra hours at work to prove your worth. Don’t give up; keep trying. You may be the next contender for the ongoing promotion or increment cycle, you never know! As of now, the financial front look quite rewarding. Mercury is just out of retrogression, which will aid in filling your coffers at great speed. If you are a single and have a crush on your colleague, you may get lucky this month. Your feelings may be reciprocated in the like manner. Grab your chance to love and get loved; go on long drives, candle-lit dinners and enjoy this phase to the fullest. Ganesha gives green signal to those who are planning to tie the knot soon. Health, however, needs to be taken care of. Watch your diet and sleeping schedules to avoid complications.",
    "date": "April 03, 2018 05:18:40 PM",
    "SunSign": "leo"
}
```


### Yearly Horoscope Request Format
 
#### GET: `https://raashiphal.herokuapp.com?type=year&&sunsign=<sunsign>`
```json
{
    "horoscope": "2018 presents a tough challenge for the Lions who hog the limelight. Not only will circumstances be difficult but they will call for an inordinate amount of patience and tolerance, and you may not always have these qualities in adequate measure. On the financial front, things will be quite satisfactory with enough money pouring from different sources for you and your family to lead a comfortable life. However, things will be far from satisfactory in some areas of life, although the stars will keep showering you with opportunities to improve things in those areas. Your familial ties will be hunky dory, but the best part is that a new love is likely to blossom in your heart, and what's more, that someone special is likely to enter into matrimonial ties with you. Your rapport with your family members is likely to improve, but malefic planets may mar your relationships with your beloved. If you are doing a partnership business, your equation with your partner could sour, so avoid arguments at any cost. Ditto for your equation with your peers and superiors, so keep a strict watch on the way you behave and the words you utter. Take care of your health, which can be done through regular meditation.",
    "date": "April 03, 2018 05:19:16 PM",
    "SunSign": "leo"
}
```



# Contributing


#### Note 1 : Data Fetch From [GaneshaSpeaks](http://www.ganeshaspeaks.com/) unofficialy.

#### Note 2 : If the API is not working properly, please open a issue.
        
