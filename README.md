# cpnt-265-achievements-SvelteKit
## Sveltekit testing for achievements
### By Jesse h

### Attributions;
Net Ninja - https://www.youtube.com/watch?v=_M-iOKo4FnE&list=PL4cUxeGkcC9hpM9ARM59Ve3jqcb54dqiP&index=2&ab_channel=TheNetNinja

image - mynamepong on https://www.flaticon.com/authors/mynamepong

This is a MUST for this tutorial, as svelte has changed; https://github.com/sveltejs/kit/discussions/5774



---

#### Things I have liked/discovered;

- dynamic (reactive) values from the script are easy!
- automatic 404 pages!? Wild.
- everything scoped? HUGE.
- folder based not file based. May take some getting used to.
- it's routing is fast.
- &lib to go to that path was awesome.
- passing a prop in was easy by changing to export.
- importing global styles for css was really nice.
- +layout@.svelte instead of __layout.reset.svelte to reset the hierarchy for all its child routes? Still unsure if right naming convention.
- load function auto fetching.

```
    {#each guides as guide}
      <li>
        <a href="/">{guide.title}</a>
      </li>
    {/each}
```
throws error Cannot read properties of undefined (reading 'length') when written. Tried to diagnose multiple ways, could not. It's fetching data from https://jsonplaceholder.typicode.com/posts . Example below.
```
{
  "userId": 1,
  "id": 1,
  "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
  "body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
}

```

