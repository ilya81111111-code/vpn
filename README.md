# vpn

{
  "outbounds": [
    {
      "tag": "WARP",
      "reserved": [
        237,
        228,
        32
      ],
      "mtu": 1280,
      "fake_packets": "5-10",
      "fake_packets_size": "40-100",
      "fake_packets_delay": "20-250",
      "fake_packets_mode": "m4",
      "private_key": "b0Eh3DULIIVE3UbToF8i8mONMkUkaHauo1Wlt3/uito=",
      "type": "wireguard",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:86e7:13b4:95d3:d290:8869/128"
      ],
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "server": "engage.cloudflareclient.com",
      "server_port": 4500
    }
  ]
}
