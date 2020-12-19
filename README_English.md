# ShiguReader

Read Comic/Play Music and Video on all platforms

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
          <img width="222px" src="https://raw.githubusercontent.com/totorowechat/ShiguReader/dev/screenshot/01.png">
      </td>
      <td align="center" valign="middle">
          <img width="222px" src="https://raw.githubusercontent.com/totorowechat/ShiguReader/dev/screenshot/02.png">
      </td>
      <td align="center" valign="middle">
          <img width="222px" src="https://raw.githubusercontent.com/totorowechat/ShiguReader/dev/screenshot/02.5.png">
      </td>
      <td align="center" valign="middle">
          <img width="222px" src="https://raw.githubusercontent.com/totorowechat/ShiguReader/dev/screenshot/03.png">
      </td>
    </tr><tr></tr>
    <tr>
      <td align="center" valign="middle">
          <img width="222px" src="https://raw.githubusercontent.com/totorowechat/ShiguReader/dev/screenshot/04.png">
      </td>
      <td align="center" valign="middle">
          <img width="222px" src="https://raw.githubusercontent.com/totorowechat/ShiguReader/dev/screenshot/05.png">
      </td>
      <td align="center" valign="middle">
          <img width="222px" src="https://raw.githubusercontent.com/totorowechat/ShiguReader/dev/screenshot/06.png">
      </td>
    </tr><tr></tr>
  </tbody>
</table>

## Getting Started

### Windows

1. Download [ShiguReader.exe](/releases/tag/2.0.0-alpha).
2. Modify `ini` file.

### OSX and Linux

#### Prerequisites

For *nix people, please install `7zip`.

#### Set up

``` shell
npm install 
npm run dev
```

If you live in China

```shell
npm install -g cnpm --registry=https://registry.npm.taobao.org
cnpm install 
npm run dev
```

### Docker

```
docker pull liwufan/shigureader
docker run -d -p <hostport>:3000 -v <comicpath>:/data liwufan/shigureader

# <hostport> is the port to be opened by the host
# <comicpath> is the directory of the files to be scanned
```

See [dockerguide](./dockerguide.md)

### Building from source

See [Readme_Env_Setup.md](./Readme_Env_Setup.md)


## Running the tests

TODO

## Contributing

TODO

## Authors

- hjyssg <the398355565@gmail.com>

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
