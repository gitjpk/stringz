# README

Initial purpose of StringZ is to allow you to have a clear follow up of the strings usage on your tennis racket through a Microsoft Excel file.

Version 3 is a full redesign - feedbacks are welcomed<br>
<b>Please notice the doc is not updated yet</b><br>

## How to "download"

Last version of the file is under /stringz/ folder.<br>
Direct link is here: https://github.com/gitjpk/stringz/raw/main/stringz/Stringz_v3.0.xlsx<br>
Direct link with sample data is here: https://github.com/gitjpk/stringz/raw/main/stringz/Stringz_v3.0_withSampleData.xlsx

## How to "install"

The file is based on several tabs.

Initial configuration is done in the **"settings" tab**.<br>
You just have to add your racket names.<br>
Current version only support 2 different rackets.<br>Most players have the same racket, so just name them Brand-Model-01 and Brand-Model-02.

The other settings that can be customized are:
- Days (absolute) to change strings: Value in days (default is 30)
- Days (absolute) to change grips: Value in days (default is 30)
- Hours played to change strings: Value in hours (default is 10)
- Hours played to change grips: Value in hours (default is 15).

<img width="400" alt="image" src="https://user-images.githubusercontent.com/26025150/211674094-1533c2d7-532d-4139-811c-3da62f672fc9.png">

## How to "upgrade"

<b>Start</b> with copy / <b>paste value only</b> the rackets.<br>
<b>Then</b>, copy / <b>paste value only</b> the datas.

To paste value, right clic, select paste special, then values:<br>
<img width="200" alt="image" src="https://user-images.githubusercontent.com/26025150/212340255-841f82c9-a8a2-4d54-a741-8f03613833e5.png">
<img width="200" alt="image" src="https://user-images.githubusercontent.com/26025150/212339673-205192ec-8586-42e8-93f2-dae86bdead85.png">


## How to use

Just add new "events" in the data tab and the dashboard will be automatically updaded.

The event types are the following:
- Strings change: Used when you re-string your racket (or when you start with a new racket). Please use unique name for strings to have stats.
- Grip change: Used when you re-grip your racket (or when you start with a new racket)
- Play: Used when you play
- New Balls: Used when you change balls.

The event can have a duration and a description. It depends the event type:
- Strings change: Just add the string name in description.
- Grip change: Just add the string name in description.
- Play: Just add the time played in duration (and any comment comment you want in description).
- New Balls: Just add the number of ball with the following syntax in description: Number <b>x</b> brand. Example (8xWilson)

## Sample data

Here is a data set that can be used to see the result of the dashboard with data:<br>
https://github.com/gitjpk/stringz/raw/main/stringz/Stringz_v2.1_withSampleData.xlsx

Sample Data:<br>
<img width="800" alt="image" src="https://user-images.githubusercontent.com/26025150/211761245-46893991-bca1-4cab-862d-ce51ee19dd1b.png">

Sample Dashboard:<br>
<img width="800" alt="image" src="https://user-images.githubusercontent.com/26025150/211760889-577c026f-6c01-4c39-8e41-ca2521405e19.png">

