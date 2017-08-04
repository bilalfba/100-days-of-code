# 100 Days Of Code - Log

### Day 0: July 7th, 2017

**Today's Progress**: CodeWars Project

**Task:** Checking max and min of a series of digits given as a string


### Day 1: 8th July 2017

**Today's Progress**: Worked on a real website to upload 1000+ product listings through a .csv file for bigCommerce. Didn't get time to do actual code. 

**Link**: [squaredubai.com](squaredubai.com)

### Day 2: 9th July 2017

**Today's Progress**: 
- Overview of dashDB and bigInsights on Bluemix.
- Machine learning W2 11 Plotting Data
- Bigcommerce Website Dev / Adding Beeketing Scripts + CSV Update
-Android Nougat Tutorial : 103-adding-menus

### Day 3: 10th July 2017

**Today's Progress**: 
Freecodecamp:
- [Truncate a String](https://www.freecodecamp.org/challenges/truncate-a-string)

**Code**
```javascript
function truncateString(str, num) {
  // Clear out that junk in your trunk
  if(num<3){
    return str.slice(0,num)+'...';  
  }
  else if(num>=str.length){
    return str;
  }
  
  else {
    
    return str.slice(0,num-3)+'...';
  }
  
}
```
- Chunky Monkey
```javascript

function chunkArrayInGroups(arr, size) {
  // Break it up.
  var newarr=[];
  for(i=0;i<arr.length;i=i+size){
    newarr.push(arr.slice(i,size+i));  
  }
  return newarr;
}

chunkArrayInGroups(["a", "b", "c", "d"], 2);
```

### Day 4: 11th July 2017

**Today's Progress**: 
- Implementing custom dashing dashboard (Ruby,HTML,CSS,JS)
- Implementing custom BBC News widget (Sublime, Ruby, Redis, Rails)
- Creating redis server instance and heroku app (didn't work :( )
- Playing with the Bluemix Tone Analyzer 
- Bigcommerce Website Dev / Researching Payment gateways 

### Day 5: 12th July 2017

**Today's Progress**: 
- Getting the calendar working on dashing (Google Calendar API, HTML,CSS,CS)
- Andrew Ng ML , Implementing Linear Regression in Octave/Matlab

### Day 6: 13th July 2017

**Today's Progress**: 
- Creating a node-red app on bluemix using 4 services (Personality Insights, Tone Analyzer, STT,TTS) and deploying it to a website.


### Day 7: 16th July 2017

**Today's Progress**: 
- Android Dev - Menu-item-groups
- Adding weather widget to dashing.io 

### Day 8: 23rd July 2017 :(

**Today's Progress**:
Freecodecamp:
- [Slasher Flick](https://www.freecodecamp.org/challenges/slasher-flick)
- [Mutations](https://www.freecodecamp.org/challenges/mutations)

***Code***
```javascript

function mutation(arr) {
  

    var string1=arr[0].toLowerCase();
    var string2=arr[1].toLowerCase();
  
    for(i=0; i<string2.length;i++){
    if (string1.indexOf(string2[i])<0)
      return false;
    
  }
  return true;
    
  //return arr[0].toLower==arr[1].toLower;
}

mutation(["hello", "hey"]);

```
```javascript

function slasher(arr, howMany) {
  // it doesn't always pay to be first

  return arr.slice(howMany);
}

slasher([1, 2, 3], 2);
```
### Day 9: 27 July 2017 :(

**Today's Progress**:
IBM Bluemix Node-RED Application:
- Created a natural language classifier application that is trained on 2000+ CSV file to automatically generate categories for new inputs. 
- Created a career path finder using Bluemix Services

### Day 10: 29 July 2017 

**Today's Progress**:
IBM Bluemix Node-RED Application:
- Created a natural language classifier application that is trained on 2000+ CSV file to automatically generate categories for new inputs. 
- Andoid Dev No.105 Menus & Toggle

### Day 11: 30 July 2017 

**Today's Progress**:
Siraj Raval - Predicting an animal's body size given it's Brain size with Linear Regression
```
import pandas as pd
from sklearn import linear_model
import matplotlib.pyplot as plt 

datafram=pd.read_fwf('brain_body.txt')
x_values=dataframe[['Brain']]
y_valuess=dataframe[['Body']]

body_reg=linear_model.LinearRegression()
body_reg.fit(x_values,y_valuess)

plt.scatter(x_values,y_valuess)
plt.plot(x_values,body_reg.predict(x_values))
plt.show()

```

### Day 12: 01 August 2017 

**Today's Progress**:
Andrew Ng Machine Learning W3 - Classification

### Day 13: 04 August 2017
**Today's Progress**
[Creating Google Home on a Raspberry Pi](https://github.com/bilalfba/google-home/)
