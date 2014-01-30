# Swagcoin [SWAG]
http://www.swagco.in/

![SwagCoin](https://31.media.tumblr.com/6a073232ffa5978ef1cb0be85446c9c3/tumblr_n04hyd0VC21tqfoe9o1_500.png)

## What is SwagCoin?
Swagcoin is like Bitcoin, but based on Litecoin, and with a lot more SWAG.
http://www.swagco.in/

## License
SwagCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## What What??

### How much SWAG can one have?
For the sake of the laws of the universe only 354,533,866 SWAG can exist.

## Fact check
1 Minute Block Targets, 4 Hour Diff Readjustments

Special reward system: Random block rewards

A regular block has a 450 SWAG reward. But then again each block has a 2.5% chance of being a bling block which pays out 2250 SWAG. AND a 0.3% chance of being a bling bling block which pays out OVER 9000 SWAG (9001 to be precise).

Alas nothing lasts forever so each block's reward be halved every 258008, you dig? (pun intended)

Maximum SWAG : 354533866 SWAG
Regular block : 450 SWAG
Bling block : 2250 SWAG (2.5% chance)
Bling Bling block : 9001 SWAG (0.3% chance)
Reward halving : 258008 blocks
Block time: 60 seconds
Retargeting : 1440 blocks

### Compile under Debian/Ubuntu

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### SWAG ports
RPC 51652
P2P 51653

