# Zentadata - SmartSupply360 use case

### How to start local environment

1. Register at https://account.zentadata.com 
2. Once registered, you will find your license key on the main page (format: xxxx-xxxx-xxxx-xxxxx-xxxx)
3. Open `docker-compose.yaml` and set

    `ZENTADATA_LICENSE_KEY: "your-license-key-here"`

4. Start local environment (in Windows you might need to grant Docker filesystem access to `dataset` folder)
```
docker compose up -d
```

### How to create data products

1. Download and start `Data Studio` client app at https://account.zentadata.com
2. Open file `smartsupply360-source.zds` and run it (hotkey F9)
3. Open file `smartsupply360-product.zds` and run it (hotkey F9)
4. Now you can see list of data products in Catalog (2nd tab) 
5. To open each data product go to Product Store (3rd tab)