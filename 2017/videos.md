# Videos

(some description of method here)

## Jan

- [Composition over Inheritance](https://www.youtube.com/watch?v=wfMtDGfHWpA)
```js
const barker = (state) => ({
  bark: () => console.log('Woof, I am ' + state.name)
})

const murderRobotDog = (name)  => {
  let state = {
    name,
    speed: 100,
    position: 0
  }
  return Object.assign(
        {},
        barker(state),
        driver(state),
        killer(state)
    )
}

const bruno =  murderRobotDog('bruno')
bruno.bark() // "Woof, I am Bruno"
```
- [Joe Stewart - Maintaining Satisfaction as a Designer](https://creativemornings.com/talks/joe-stewart/2)
```
- Designer is always wrong. 
- Design is way of thinking. A media of thinking
- Methology to learn and progress
- One thing that is great: 
- Being inspired 
> The diference between good design and just ok design
> The diference between being happy to work on something and just working
- Inspiration is one second: seeing the finish line before you start
- Nobody is good yet in digital.
```
