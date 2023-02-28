### @activities true

# Den røde løber

## Lyt efter en hændelse

### Step 1

Fra menuen ``||player:Spiller||`` skal du trække en ``||player:på spilleren gå||`` blok ind i arbejdsområdet.

```blocks
player.onTravelled(WALK, function () {
	
})
```

### Place some flowers (Should be in danish?)

Under ``||blocks:Blokke||`` finder du blokken ``||blocks:placer ved||``. Træk den hen så den sætter sig fast inde i ``||player:på spilleren gå||`` blokken

```blocks
player.onTravelled(WALK, function () {
    blocks.place(GRASS, pos(0, 0, 0))
})
```

## Second activity

### Step 1
