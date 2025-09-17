## Dream Team

As part of onboarding a new team member, we use this Dream Team page so the person can make their `first commit`. This way, they can test their GitHub access, open their first Pull Request, and share a bit about themselves as an introduction 🙂

### Adding your profile

🚨 You need to have access to the `renatoaug` organization on GitHub. If you don’t have it yet, talk to your Engineering Manager.

---

1. Clone the project to your machine

```bash
git clone git@github.com:renatoaug/culture.git
```

2. Create a new branch

```bash
git checkout -b docs/{SEU_NOME}-profile
```

3. Look for the file that represents your area inside `/dream-team`

```
📂 dream-team
┣ 📃 team-data.js
┣ 📃 team-dev.js
┣ 📃 team-product.js
```

4. Open the file and add your information at the end

```js
{
  name: 'Et Bilu',
  role: devRoles.full_stack,
  description: 'Lorem Ipsum...',
  github: 'GitHub URL (if you have one)',
  linkedin: 'LinkedIn URL (if you have one)',
  avatar: 'Image URL'
}
```

If you want to add your age or how long you’ve been working in the field, use `getTotalYears('dd/mm/yyyy')`

```js
{
  description: "Hi, I am getTotalYears('dd/mm/yyyy') years old and I enjoy yada yada...",
}
```

5. Follow the steps in [README](../README.md) to run the project, then open `/culture/dream-team/` in your browser to check if everything looks good!

   Validating our work is a very important part of our day-to-day 😉

6. Commit your changes

```bash
git add .
git commit -m "docs(dream_team): add {YOUR_NAME} profile"
git push origin docs/{SEU_NOME}-profile
```

7. Open a Pull Request using the template

```md
![gif-or-image]()

### What?

Adding my profile to the Dream Team.

### Why?

My first PR 🚀
```

8. After receiving 2 approvals, you can merge your PR and check if your profile appears on the page 🍻
