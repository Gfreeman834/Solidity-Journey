# Gas and Gas Prices

Bu bölüm Solidity'de **gas** kavramını ve gas tüketimini örneklerle açıklar.

## Gas Nedir?

- Ethereum ağında her işlem (transaction) **gas** harcar.
- Gönderdiğiniz tüm gas tükenirse işlem **başarısız** olur.
- İşlem başarısız olduğunda **state değişiklikleri geri alınır**.
- Harcanan gas **iade edilmez**.

## Dosyalar

| Dosya | Açıklama |
|-------|----------|
| `Gas and Gas Prices.sol` | Sonsuz döngü ile gas tüketimi örneği |

## Contract: `Gas`

- `forever()` fonksiyonu sonsuz bir `while` döngüsü çalıştırır.
- Döngü gönderilen gas bitene kadar devam eder, sonra işlem revert olur.
- Bu örnek, gas limitinin aşıldığında işlemin nasıl başarısız olduğunu gösterir.

## Kullanım

Contract'ı derleyip test ağında veya yerel ortamda deploy edebilirsiniz. `forever()` çağrıldığında gas tükenene kadar döngü çalışır ve işlem başarısız olur.

---

## GitHub'a Yükleme

Bu klasörü [Solidity-Journey](https://github.com/Gfreeman834/Solidity-Journey) reposuna eklemek için:

1. Repoyu klonlayın (henüz yoksa):
   ```bash
   git clone https://github.com/Gfreeman834/Solidity-Journey.git
   cd Solidity-Journey
   ```

2. Bu klasördeki tüm dosyaları (`Gas and Gas Prices` klasörü ile birlikte) klonladığınız repo içine kopyalayın.

3. Değişiklikleri ekleyip commit edin:
   ```bash
   git add "Gas and Gas Prices"
   git commit -m "Add Gas and Gas Prices section"
   ```

4. GitHub'a gönderin:
   ```bash
   git push origin main
   ```
