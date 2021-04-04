# Nasıl İndirilir?

```js
npm i foe.db```

# Nasıl Kullanılır?

const db = require('foe.db')

# Veri Kaydetme - Çekme

db.set(`veri.1`)
db.get(`veri.1`)
db.fetch(`veri.1`)

# Veri Silme

db.delete(`veri.1`)
db.deleteAll()