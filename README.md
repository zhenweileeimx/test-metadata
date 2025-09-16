# Test Metadata Collection - NFT Metadata

This repository hosts the metadata for a **Test NFT Collection** deployed on Immutable zkEVM Testnet.

## Collection Details

- **Contract Address**: `0x77118E5038d5db44b1DA7DBB7B00087F2406bC06`
- **Network**: Immutable zkEVM Testnet
- **Total Supply**: 9 NFTs
- **Collection Name**: Test Collection
- **Symbol**: TEST

## Metadata Structure

The metadata follows the ERC-721 standard and is hosted as individual JSON files:

```
metadata/
├── 1.json  # Happy Character (Common)
├── 2.json  # Sleepy Character (Common)  
├── 3.json  # Crying Character (Uncommon)
├── 4.json  # Angry Character (Rare)
├── 5.json  # Love Character (Rare)
├── 6.json  # Surprised Character (Uncommon)
├── 7.json  # Cool Character (Epic)
├── 8.json  # Thinking Character (Common)
└── 9.json  # Golden Character (Legendary)
```

## Base URI

The contract uses the following base URI:
```
https://raw.githubusercontent.com/[USERNAME]/test-metadata/main/metadata/
```

## NFT Collection

### Rarity Distribution
- **Common**: 3 NFTs (33.3%)
- **Uncommon**: 2 NFTs (22.2%)  
- **Rare**: 2 NFTs (22.2%)
- **Epic**: 1 NFT (11.1%)
- **Legendary**: 1 NFT (11.1%)

### Characters
Each NFT features different expressions and traits:
1. **Happy Character** - Cheerful and bright
2. **Sleepy Character** - Peaceful and drowsy
3. **Crying Character** - Emotional and touching
4. **Angry Character** - Fierce and determined
5. **Love Character** - Romantic with heart eyes
6. **Surprised Character** - Shocked and amazed
7. **Cool Character** - Stylish with sunglasses
8. **Thinking Character** - Contemplative and thoughtful
9. **Golden Character** - Majestic with golden aura

## Images

All images are AI-generated using Pollinations.ai with anime/kawaii style prompts featuring blue characters in different emotional states.

## Usage

This metadata is designed to work with:
- OpenSea and other NFT marketplaces
- Immutable X ecosystem
- Any ERC-721 compatible platform

## License

This project is open source and available under the MIT License.