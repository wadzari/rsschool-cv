# Konstantin Arabei

**Frontend Developer**
Tashkent, Uzbekistan | <arabey.k@gmail.com> | [GitHub](https://github.com/wadzari) | Discord nickname: Konstantin (@wadzari)

## Experience

**Koop Technologies**
*Dubai, OAE | June 2022 – April 2025 | 2 years 9 months*

* Developed and maintained web-based applications using React, JavaScript, and TypeScript.

* Created reusable UI components, improving consistency across the product and reducing development time for new features.

## Skills

* **Programming Languages**: JavaScript, TypeScript
* **Frameworks and Libraries**: React, Nextjs, Tailwind CSS, Ant Design, React Query
* **Tools**: Git, Jira

## Code Example

```js
const threeSum = function (nums) {
    nums.sort((a, b) => a - b);
    const res = []

    for (let i = 0; i < nums.length; i++) {
        if (i > 0 && nums[i] === nums[i - 1]) {
            continue;
        }

        let l = i + 1;
        let r = nums.length - 1;

        while (l < r) {
            let sum = nums[i] + nums[l] + nums[r]

            if (sum < 0) {
                l++
            } else if (sum > 0) {
                r--
            } else {
                res.push([nums[i], nums[l], nums[r]])
                l++

                while (nums[l] === nums[l - 1] && l < r) {
                    l++
                }
            }
        }
    }

    return res
};
```

## Education

**International Economy**
*Khabarovsk State Academy of Economics and Law | 2009 – 2014*
