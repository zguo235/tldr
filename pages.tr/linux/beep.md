# beep

> Bilgisayar hoparlörlünü öttürme aracı.
> Daha fazla bilgi için: <https://github.com/spkr-beep/beep>.

- Öttürme sesi oynat:

`beep`

- Tekrar eden öttürme sesi oynat:

`beep -r {{repetitions}}`

- Belirtilen frekans (Hz) ve sürede (milisaniye) oynamak üzere öttürme sesi oynat:

`beep -f {{frekans}} -l {{süre}}`

- Hep bir frekans ve süreyi ayrı bir öttürme sesi olarak oynat:

`beep -f {{frekans}} -l {{süre}} -n -f {{frekans}} -l {{süre}}`

- C major boyutunda öttürme sesi oynat:

`beep -f {{262}} -n -f {{294}} -n -f {{330}} -n -f {{349}} -n -f {{392}} -n -f {{440}} -n -f {{494}} -n -f {{523}}`
