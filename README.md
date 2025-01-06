## 希望

好东西都应该让我白嫖！

## 我

是 Hanxven，一位喜欢**可爱兔耳娘**和**可爱猫耳娘**的不可爱编程人。

或者可以叫我：Mr. Hanwen。

```ts
import { useHanxven, useBunnyGirl, useNekoGirl, useEffectEx as useEffect, lessThan, equals, type InterestConfig } from 'hanxven'

const basicConfig: InterestConfig = {
  age: lessThan(18),
  type: equals('anime'),
  kawaii: equals(true)
}

const { happy } = useHanxven()
const bunnyGirl = useBunnyGirl(basicConfig)
const nekoGirl = useNekoGirl(basicConfig)

useEffect(happy, [bunnyGirl, nekoGirl])
```

## ⭐

<img align="left" src="https://github-readme-stats.vercel.app/api?username=Hanxven&show_icons=true&theme=vue-dark"/>
