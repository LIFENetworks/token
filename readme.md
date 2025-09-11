 cmd for init token:
 

``` 
spl-token create-token \
 --program-2022 \
 --enable-metadata \
 --enable-close \
 --enable-freeze \
 --decimals 9 \
 --fee-payer AUTFUXnVWmvbuahr6JazdAJtm36Xc65Yuf1Zc2DXJBof.json \
 --mint-authority AUTFUXnVWmvbuahr6JazdAJtm36Xc65Yuf1Zc2DXJBof \
 LiFem4cbDpXd3vEqmfwpjd9mD7q9yTzosbGF3AC1GzV.json
 ```

cmd for init metadata :

```
spl-token initialize-metadata \
  LiFem4cbDpXd3vEqmfwpjd9mD7q9yTzosbGF3AC1GzV \
  "Life" \
  "LIFE" \
  "https://arweave.net/your-metadata-hash" \
  --program-2022 \
  --fee-payer AUTFUXnVWmvbuahr6JazdAJtm36Xc65Yuf1Zc2DXJBof.json \
  --update-authority AUTFUXnVWmvbuahr6JazdAJtm36Xc65Yuf1Zc2DXJBof
```
