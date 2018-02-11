## Setup

```
git clone git@github.com:spleenteo/csuticonzero.git
```

And then:

```
bundle install
yarn install
```

## How to deploy

First you need to add the production remote:

```
git remote add production git@github.com:spleenteo/csuticonzero.git
```

Then just git push to production, Netlify will take care of everything:

```
git push production
```
