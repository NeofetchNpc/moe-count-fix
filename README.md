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
![Gelbooru](https://count.neastooid.xyz/get/@demo?theme=gelbooru)
</details>

------------

## Try It!
[https://count.neastooid.xyz](https://count.neastooid.xyz)

------------

# Setup Deploying on your own server
```shell
$ git clone https://github.com/NeofetchNpc/moe-count.git
$ cd moe-count
$ yarn install

$ yarn start
```

# Configuration

setup config.yaml
```yaml
app:
  site: https://count.neastooid.xyz # your website must
  port: 3000

db:
  type: mongodb # sqlite or mongodb
```

[mongodb.js](https://github.com/NeofetchNpc/moe-count-fix/blob/main/db/mongodb.js) replace this code with your mongodb! 
```js
// the default mongodb url (local server)
const mongodbURL = 'mongodb+srv://localhost'
```

## Credits

*   [moebooru](https://github.com/moebooru/moebooru)
*   [NeofetchNpc](https://github.com/NeofetchNpc)
*   [journey-ad](https://github.com/journey-ad)
*   [Fuwn](https://github.com/Fuwn)

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FNeofetchNpc%2Fmoe-count.svg?type=large&issueType=license)](https://app.fossa.com/projects/git%2Bgithub.com%2FNeofetchNpc%2Fmoe-count?ref=badge_large&issueType=license)
