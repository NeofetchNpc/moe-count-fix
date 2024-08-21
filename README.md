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
$ git clone https://github.com/NeofetchNpc/moe-count.git
$ cd moe-count
$ yarn install

$ yarn start
```

### Configuration

setup config.yaml

```yaml
app:
  site: https://count.neastooid.xyz # your website must
  port: 3000

db:
  type: mongodb # sqlite or mongodb
```

fill .env with this, if the .env file is named .env.example immediately rename it to .env 
```.env
DB_URL="mongodb+srv://account:passwd@***.***.***.mongodb.net/db_count"
```

## Credits

*   [moebooru](https://github.com/moebooru/moebooru)
*   [NeofetchNpc](https://github.com/NeofetchNpc)

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter?ref=badge_large)
