# Directory-js - Server

Creating a `directory.io` website, only using server side nodejs (as `directory.io` do) in 3 different way:

1. [Command line tool](#command-line-tool) (DONE)
2. A basic nodejs.httpServer (TODO)
3. Using `express.js` web application framework (TODO)

---

* [INITIALIZE](INITIALIZE.md)
* [INSTALL](INSTALL.md)
* [TEST](TEST.md)

---

## Command line tool

``` c
$ echo '{"offset":"123", "delta": 3}' | node cmd-dump-keys.js | jq
[
  {
    "index": "123",
    "wif": {
      "extended": "5HpHagT65TZzG1PH3CSu63k8DbpvD8s5ip4nEB3kEsreQYt2Gms",
      "compressed": "KwDiBf89QgGbjEhKnhXJuH7LrciVrZi3qYjgd9M7rFU86d9GNkvq"
    },
    "address": {
      "extended": "1HHKanEL28o5Nrui8byqTNwFtWpdVEPzw5",
      "compressed": "141fTonryMQxmkKcba9FstmyQv3tqdBzTY"
    }
  },
  {
    "index": "124",
    "wif": {
      "extended": "5HpHagT65TZzG1PH3CSu63k8DbpvD8s5ip4nEB3kEsreQbpfitE",
      "compressed": "KwDiBf89QgGbjEhKnhXJuH7LrciVrZi3qYjgd9M7rFU8785hwgzZ"
    },
    "address": {
      "extended": "1KmobiUwSFcKyDX2z1Ss2TVL5yLq2BnxrS",
      "compressed": "1FFYArxgMbCLi366pCrgdXfzGBBMGssX9"
    }
  },
  {
    "index": "125",
    "wif": {
      "extended": "5HpHagT65TZzG1PH3CSu63k8DbpvD8s5ip4nEB3kEsreQi1XfkP",
      "compressed": "KwDiBf89QgGbjEhKnhXJuH7LrciVrZi3qYjgd9M7rFU87cwUJZ5H"
    },
    "address": {
      "extended": "1QCoHemDLMTaSJb7heXUHLsu6YPyu5iDEv",
      "compressed": "12muChUsDE5KRdkFDKhRxSAHe5JD9VoPA9"
    }
  }
]

```
