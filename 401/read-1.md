# Node Ecosystem, TDD, CI/CD

## Array.map()

the map function creates a new array populated with the retuen values of called the callback that passed to the map function on every single element in the calling array 

## Array.reduce()

the reduce function executes the callback (also called reducer) on every single element in the calling array resulting one single output

## superAgent

superAgent with normal promises :

```
superagent
  .get(apiUrl)
  .then(data=>{
    return data.body.results;
  })
  .then(data=>{
    //console.log(data)
    return data.map(x=>{
      return {
        [x.name]:x.url
      }
    })
   
  })
  .then(data=>{
    console.log(data);
  })
  ```

  superAgent with asyn/await promises :
```
  async function getCityInfo(cityName){
  let apiUrl=`https://geocode.xyz/${cityName}?json=1`;
  let data=await superagent.get(apiUrl)
  let obj={
    city_name:data.body.standard.city,
    longitude:data.body.longt,
    latitude:data.body.latt
  }
  console.log(obj)
}
getCityInfo("irbid").catch(error=>console.log(error));
```

## promises

promises is method to tell javascript what to next when finishing an in-bakground job

## callbacks

Are all callback functions considered to be Asynchronous? Why or Why Not?

No,In javascript a functions is consider to be Asynchronous when and only when it returns A Promise

in general , the async callbaks is the connection between the in-background code and  the main code ,
when the in-background code is finish, the async callbaks will come to the main code with the result of the
in-background code

# References 

1. https://developer.mozilla.org/en-US/
