# The Artivist

## Entities

### User 

- id: string
- name: string
- email: string
- password: string - criptografado
- type: string - "ngo", "activist", "artist", "doador"
- img_perfil: string - url - 
- wallet_address: string - wallet address - 0x17eDfB8a794ec4f13190401EF7aF1c17f3cc90c5 - Fase 2

> if type == artist
phone_number: string
description: string
address: string
postal_code: string

### Campaign

- title: string
- description: string
- category_id: int
- artist_id: int
- nft_img: url
- nft_price: number
- nft_quantity: number

### campaign_category | "Feminism", "Healt", "Animals", "Environment"

- id: string
- name: string


