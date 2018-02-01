Ukázkový web nad frameworkem Spress
===================================

Vytvoření webu
--------------

 * stáhněte PHAR soubor s Spressem [zde](http://spress.yosymfony.com/download/)
 * vytvořte lokální soubor `config_lokal.yml`
   * tento soubor není nutné commitovat, je nutný pouze pokud vás více vyvíjí
     na fyzicky stejném počítači (každý pak volte jiné číslo portu!)

```
port: 4001
```

 * spusťte generátor

```shell
php -n spress.phar site:build --server --watch --env lokal
```

 * otevřete http://localhost:4001 (popř. opravte číslo portu)

