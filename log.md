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
```

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


