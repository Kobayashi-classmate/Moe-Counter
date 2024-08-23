# Moe-Counter

多种风格可选的萌萌计数器

![Moe-Counter](https://api.capiry.com/counte/get/@Kobayashi-classmate?theme=rule34)

<details>
<summary>More theme</summary>

##### asoul
![asoul](https://api.capiry.com/counte/get/@demo?theme=asoul)

##### moebooru
![moebooru](https://api.capiry.com/counte/get/@demo?theme=moebooru)

##### rule34
![Rule34](https://api.capiry.com/counte/get/@demo?theme=rule34)

##### gelbooru
![Gelbooru](https://api.capiry.com/counte/get/@demo?theme=gelbooru)</details>

## Demo
[https://api.capiry.com/counte](https://api.capiry.com/counte/get/@demo?theme=asoul)

## Usage

### Install

#### Run on Replit

- Open the url [https://replit.com/@journeyad/Moe-Counter](https://replit.com/@journeyad/Moe-Counter)
- Just hit the **Fork** button
- And hit the **Run** button

#### Deploying on your own server

```shell
$ git clone https://github.com/Kobayashi-classmate/Moe-Counter.git
$ cd Moe-Counter
$ yarn install

$ yarn start
```

### Configuration

`config.yml`

```yaml
app:
  # site: https://count.getloli.com # your website
  port: 3000

db:
  type: sqlite # sqlite or mongodb
```

If you use mongodb, you need to specify the environment variable `DB_URL`

```shell
# eg:
export DB_URL=mongodb+srv://account:passwd@***.***.***.mongodb.net/db_count
```

replit can use Secrets, [documentation](https://docs.replit.com/programming-ide/storing-sensitive-information-environment-variables)

```
DB_URL="mongodb+srv://account:passwd@***.***.***.mongodb.net/db_count"
```

## Credits

*   [replit](https://replit.com/)
*   [A-SOUL_Official](https://space.bilibili.com/703007996)
*   [moebooru](https://github.com/moebooru/moebooru)
*   rule34.xxx NSFW
*   gelbooru.com NSFW
*   [Icons8](https://icons8.com/icons/set/star)

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter?ref=badge_large)
