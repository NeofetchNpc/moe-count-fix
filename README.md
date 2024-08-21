# Moe-Counter-Fixxed

![Moe-Counter](https://count.neastooid.xyz/get/@demo?theme=asoul)

<details>
<summary>More theme</summary>

##### asoul
![asoul](https://count.neastooid.xyz/get/@demo?theme=asoul)

##### moebooru
![moebooru](https://count.neastooid.xyz/get/@demo?theme=moebooru)

##### rule34
![Rule34](https://count.neastooid.xyz/get/@demo?theme=rule34)

##### gelbooru
![Gelbooru](https://count.neastooid.xyz/get/@demo?theme=gelbooru)</details>

## Demo
[https://count.getloli.com](https://count.neastooid.xyz)

#### Deploying on your own server

```shell
$ git clone https://github.com/journey-ad/Moe-Counter.git
$ cd Moe-Counter
$ yarn install

$ yarn start
```

### Configuration

`config.yml`

```yaml
app:
  site: https://count.getloli.com # your website
  port: 3000

db:
  type: mongodb # sqlite or mongodb
```

If you use mongodb, you need to specify the environment variable `DB_URL`
replit can use Secrets, [documentation](https://docs.replit.com/programming-ide/storing-sensitive-information-environment-variables)
```
DB_URL="mongodb+srv://account:passwd@***.***.***.mongodb.net/db_count"
```

## Credits

*   [moebooru](https://github.com/moebooru/moebooru)
*   [NeofetchNpc](https://github.com/NeofetchNpc)

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter?ref=badge_large)
