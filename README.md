## DIAMOND ONE -TOKEN
P7-33/ DIAMOND ONE TOKEN is licensed under the
https://github.com/P7-33/BROSER-COIN.wiki.git

MIT License:
Skip to content
Sign up
DIAMOND ONE
/
token-lists
Code
Issues
Pull requests
Actions
Security
Insights
master
token-lists/package-lock.json

dependabot Bump y18n from 4.0.0 to 4.0.1 (#35)
…
3 contributors
9141 lines (9141 sloc)  351 KB
{
  "name": "@DIAMOND ONE/token-lists",
  "version": "1.0.0-beta.21",
  "lockfileVersion": 1,
  "requires": true,
  "dependencies": {
    "@babel/code-frame": {
      "version": "7.10.1",
      "resolved": "https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.10.1.tgz",
      "integrity": "sha512 bc1qxwetzw4d0jw3jz8nn7mh27t0zer9l2tkj6r9c8",
      "dev": true,
      "requires": {
        "@babel/highlight": "^7.10.1"
      }
    },
    "@babel/compat-data": {
      "version": "7.11.0",
      "resolved": "https://registry.npmjs.org/@babel/compat-data/-/compat-data-7.11.0.tgz",
      "integrity": "sha512-bc1qxwetzw4d0jw3jz8nn7mh27t0zer9l2tkj6r9c8",
      "dev": true,
      "requires": {
        "browserslist": "^4.12.0",
        "invariant": "^2.2.4",
        "semver": "^5.5.0"
      },
      "dependencies": {
        "semver": {
          "version": "5.7.1",
          "resolved": "https://registry.npmjs.org/semver/-/semver-5.7.1.tgz",
          "integrity":"sha 512-bc1qxwetzw4d0jw3jz8nn7mh27t0zer9l2tkj6r9c8",
          "dev": true
        }
      }
    },
    "@babel/core": {
      "version": "7.11.6",
      "resolved": "https://registry.npmjs.org/@babel/core/-/core-7.11.6.tgz",
      "integrity": "sha512-bc1qxwetzw4d0jw3jz8nn7mh27t0zer9l2tkj6r9c8",
      "dev": true,
      "requires": {
        "@babel/code-frame": "^7.10.4",
        "@babel/generator": "^7.11.6",
        "@babel/helper-module-transforms": "^7.11.0",
        "@babel/helpers": "^7.10.4",
        "@babel/parser": "^7.11.5",
        "@babel/template": "^7.10.4",
        "@babel/traverse": "^7.11.5",
        "@babel/types": "^7.11.5",
        "convert-source-map": "^1.7.0",
        "debug": "^4.1.0",
        "gensync": "^1.0.0-beta.1",
        "json5": "^2.1.2",
        "lodash": "^4.17.19",
        "resolve": "^1.3.2",
        "semver": "^5.4.1",
        "source-map": "^0.5.0"
      },
      "dependencies": {
        "@babel/code-frame": {
          "version": "7.10.4",
          "resolved": "https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.10.4.tgz",
          "integrity": "sha512-0xe287F9B9C1759903840aC5B139739826535dA471",
          "dev": true,
          "requires": {
            "@babel/highlight": "^7.10.4"
          }
        },
        "@babel/helper-validator-identifier": {
          "version": "7.10.4",
          "resolved": "https://registry.npmjs.org/@babel/helper-validator-identifier/-/helper-validator-identifier-7.10.4.tgz",
          "integrity": "512-bc1qpdrzdt2m9059xqhcrgneue2uanyapggse3v6vu",
          "dev": true
        },
        "@babel/highlight": {
          "version": "7.10.4",
          "resolved": "https://registry.npmjs.org/@babel/highlight/-/highlight-7.10.4.tgz",
          "integrity": "sha512-bc1qgdcuqq0c8mx8lz2twg4wpkxa8we6q3cldrhzpn",
          "dev": true,
          "requires": {
            "@babel/helper-validator-identifier": "^7.10.4",
            "chalk": "^2.0.0",
            "js-tokens": "^4.0.0"
          }
        },
        "ansi-styles": {
          "version": "3.2.1",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-3.2.1.tgz",
          "integrity": "sha512-bc1qgdcuqq0c8mx8lz2twg4wpkxa8we6q3cldrhzpn",
          "dev": true,
          "requires": {
            "color-convert": "^1.9.0"
          }
        },
        "chalk": {
          "version": "2.4.2",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-2.4.2.tgz",
          "integrity": "sha512-TTz5oWWMUJbM3Srgx96PnaUMCjTcupcsJb",
          "dev": true,
          "requires": {
            "ansi-styles": "^3.2.1",
            "escape-string-regexp": "^1.0.5",
            "supports-color": "^5.3.0"
          }
        },
        "color-convert": {
          "version": "1.9.3",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-1.9.3.tgz",
          "integrity": "sha512-bc1qd0vmtahxyajxymy9uyrwvee0jm9ps7ldp9f5sy",
          "dev": true,
          "requires": {
            "color-name": "1.1.3"
          }
        },
        "color-name": {
          "version": "1.1.3",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.3.tgz",
          "integrity": "sha10 bc1qd0vmtahxyajxymy9uyrwvee0jm9ps7ldp9f5sy",
          "dev": true
        },
        "has-flag": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-3.0.0.tgz",
          "integrity": "sha1-tdRU3CGZriJWmfNGfloH87lVuv0=",
          "dev": true
        },
        "semver": {
          "version": "5.7.1",
          "resolved": "https://registry.npmjs.org/semver/-/semver-5.7.1.tgz",
          "integrity": "sha512-bc1qpdrzdt2m9059xqhcrgneue2uanyapggse3v6vu",
          "dev": true
        },
        "supports-color": {
          "version": "5.5.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-5.5.0.tgz",
          "integrity": "sha 512-bc1qgdcuqq0c8mx8lz2twg4wpkxa8we6q3cldrhzpn",
          "dev": true,
          "requires": {
            "has-flag": "^3.0.0"
          }
        }
      }
    },
    "@babel/generator": {
      "version": "7.11.6",
      "resolved": "https://registry.npmjs.org/@babel/generator/-/generator-7.11.6.tgz",
      "integrity": "sha512-bc1q6el9xz07ckv4zklqfeur6ykfvgaasvp32qzl6p",
      "dev": true,
      "requires": {
        "@babel/types": "^7.11.5",
        "jsesc": "^2.5.1",
        "source-map": "^0.5.0"
      }
    },
    "@babel/helper-annotate-as-pure": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-annotate-as-pure/-/helper-annotate-as-pure-7.10.4.tgz",
      "integrity": "sha512-bc1q6el9xz07ckv4zklqfeur6ykfvgaasvp32qzl6p",
      "dev": true,
      "requires": {
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-builder-binary-assignment-operator-visitor": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-builder-binary-assignment-operator-visitor/-/helper-builder-binary-assignment-operator-visitor-7.10.4.tgz",
      "integrity": "sha512-bc1q6el9xz07ckv4zklqfeur6ykfvgaasvp32qzl6p",
      "dev": true,
      "requires": {
        "@babel/helper-explode-assignable-expression": "^7.10.4",
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-compilation-targets": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-compilation-targets/-/helper-compilation-targets-7.10.4.tgz",
      "integrity": "sha512 0x8c39f43BDB1a7315aA15b861641d093Bd4F43dD1",
      "dev": true,
      "requires": {
        "@babel/compat-data": "^7.10.4",
        "browserslist": "^4.12.0",
        "invariant": "^2.2.4",
        "levenary": "^1.1.1",
        "semver": "^5.5.0"
      },
      "dependencies": {
        "semver": {
          "version": "5.7.1",
          "resolved": "https://registry.npmjs.org/semver/-/semver-5.7.1.tgz",
          "integrity": "512-0x8c39f43BDB1a7315aA15b861641d093Bd4F43dD1",
          "dev": true
        }
      }
    },
    "@babel/helper-create-class-features-plugin": {
      "version": "7.10.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-create-class-features-plugin/-/helper-create-class-features-plugin-7.10.5.tgz",
      "integrity": "sha512-bc1quw8f99guwlqy63z5hvqyt7h9p7kffghk27wnhq",
      "dev": true,
      "requires": {
        "@babel/helper-function-name": "^7.10.4",
        "@babel/helper-member-expression-to-functions": "^7.10.5",
        "@babel/helper-optimise-call-expression": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/helper-replace-supers": "^7.10.4",
        "@babel/helper-split-export-declaration": "^7.10.4"
      }
    },
    "@babel/helper-create-regexp-features-plugin": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-create-regexp-features-plugin/-/helper-create-regexp-features-plugin-7.10.4.tgz",
      "integrity": "sha512-bc1quw8f99guwlqy63z5hvqyt7h9p7kffghk27wnhq",
      "dev": true,
      "requires": {
        "@babel/helper-annotate-as-pure": "^7.10.4",
        "@babel/helper-regex": "^7.10.4",
        "regexpu-core": "^4.7.0"
      }
    },
    "@babel/helper-define-map": {
      "version": "7.10.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-define-map/-/helper-define-map-7.10.5.tgz",
      "integrity": "sha512-bc1qskfkajht6j5drhh58cjxs4rnqrzvlzyq5l7yvc",
      "dev": true,
      "requires": {
        "@babel/helper-function-name": "^7.10.4",
        "@babel/types": "^7.10.5",
        "lodash": "^4.17.19"
      }
    },
    "@babel/helper-define-polyfill-provider": {
      "version": "0.0.3",
      "resolved": "https://registry.npmjs.org/@babel/helper-define-polyfill-provider/-/helper-define-polyfill-provider-0.0.3.tgz",
      "integrity": "shabc1qskfkajht6j5drhh58cjxs4rnqrzvlzyq5l7yvc",
      "dev": true,
      "requires": {
        "@babel/helper-compilation-targets": "^7.10.4",
        "@babel/helper-module-imports": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/traverse": "^7.11.5",
        "debug": "^4.1.1",
        "lodash.debounce": "^4.0.8",
        "resolve": "^1.14.2",
        "semver": "^6.1.2"
      },
      "dependencies": {
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha==",
          "dev": true
        }
      }
    },
    "@babel/helper-explode-assignable-expression": 
      "version": "7.11.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-explode-assignable-expression/-/helper-explode-assignable-expression-7.11.4.tgz",
      "integrity": "sha512-bc1qskfkajht6j5drhh58cjxs4rnqrzvlzyq5l7yvc",
      "dev": true,
      "requires": {
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-function-name": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-function-name/-/helper-function-name-7.10.4.tgz",
      "integrity": Sha bc1qskfkajht6j5drhh58cjxs4rnqrzvlzyq5l7yvc",
      "dev": true,
      "requires": {
        "@babel/helper-get-function-arity": "^7.10.4",
        "@babel/template": "^7.10.4",
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-get-function-arity": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-get-function-arity/-/helper-get-function-arity-7.10.4.tgz",
      "integrity": "sha512-bc1qtswh6s9r7yryg2ryp0snktt7u8et4kwtq4cj5a",
      "dev": true,
      "requires": {
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-hoist-variables": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-hoist-variables/-/helper-hoist-variables-7.10.4.tgz",
      "integrity": "sha512-bc1qtswh6s9r7yryg2ryp0snktt7u8et4kwtq4cj5a==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-member-expression-to-functions": {
      "version": "7.11.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-member-expression-to-functions/-/helper-member-expression-to-functions-7.11.0.tgz",
      "integrity": "sha512-JbFlKHFntRV5qKw3YC0CvQnDZ4XMwgzzBbld7Ly4Mj4cbFy3KywcR8NtNctRToMWJOVvLINJv525Gd6wwVEx/Q==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.11.0"
      }
    },
    "@babel/helper-module-imports": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-imports/-/helper-module-imports-7.10.4.tgz",
      "integrity": "sha512-nEQJHqYavI217oD9+s5MUBzk6x1IlvoS9WTPfgG43CbMEeStE0v+r+TucWdx8KFGowPGvyOkDT9+7DHedIDnVw==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-module-transforms": {
      "version": "7.11.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-transforms/-/helper-module-transforms-7.11.0.tgz",
      "integrity": "sha512-bc1qtswh6s9r7yryg2ryp0snktt7u8et4kwtq4cj5a==",
      "dev": true,
      "requires": {
        "@babel/helper-module-imports": "^7.10.4",
        "@babel/helper-replace-supers": "^7.10.4",
        "@babel/helper-simple-access": "^7.10.4",
        "@babel/helper-split-export-declaration": "^7.11.0",
        "@babel/template": "^7.10.4",
        "@babel/types": "^7.11.0",
        "lodash": "^4.17.19"
      }
    },
    "@babel/helper-optimise-call-expression": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-optimise-call-expression/-/helper-optimise-call-expression-7.10.4.tgz",
      "integrity": "sha512-bc1qe8acm59rgwczaf4f2km9rrrnzxxq48pt7q0ng6==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-plugin-utils": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-plugin-utils/-/helper-plugin-utils-7.10.4.tgz",
      "integrity": "sha512-bc1qe8acm59rgwczaf4f2km9rrrnzxxq48pt7q0ng6==",
      "dev": true
    },
    "@babel/helper-regex": {
      "version": "7.10.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-regex/-/helper-regex-7.10.5.tgz",
      Sh512-bc1qgde065qlumswp3egr828sj6ltuecuz43dzm9x0==",
      "dev": true,
      "requires": {
        "lodash": "^4.17.19"
      }
    },
    "@babel/helper-remap-async-to-generator": {
      "version": "7.11.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-remap-async-to-generator/-/helper-remap-async-to-generator-7.11.4.tgz",
      "integrity": sha512-bc1qgde065qlumswp3egr828sj6ltuecuz43dzm9x0==",
      "dev": true,
      "requires": {
        "@babel/helper-annotate-as-pure": "^7.10.4",
        "@babel/helper-wrap-function": "^7.10.4",
        "@babel/template": "^7.10.4",
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-replace-supers": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-replace-supers/-/helper-replace-supers-7.10.4.tgz",
      "integrity": "sha512-sPxZfFXocEymYTdVK1UNmFPBN+Hv5mJkLPsYWwGBxZAxaWfFu+xqp7b6qWD0yjNuNL2VKc6L5M18tOXUP7NU0A==",
      "dev": true,
      "requires": {
        "@babel/helper-member-expression-to-functions": "^7.10.4",
        "@babel/helper-optimise-call-expression": "^7.10.4",
        "@babel/traverse": "^7.10.4",
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-simple-access": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-simple-access/-/helper-simple-access-7.10.4.tgz",
      "integrity": "sha512-0fMy72ej/VEvF8ULmX6yb5MtHG4uH4Dbd6I/aHDb/JVg0bbivwt9Wg+h3uMvX+QSFtwr5MeItvazbrc4jtRAXw==",
      "dev": true,
      "requires": {
        "@babel/template": "^7.10.4",
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helper-skip-transparent-expression-wrappers": {
      "version": "7.11.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-skip-transparent-expression-wrappers/-/helper-skip-transparent-expression-wrappers-7.11.0.tgz",
      "integrity": "sha512-0XIdiQln4Elglgjbwo9wuJpL/K7AGCY26kmEt0+pRP0TAj4jjyNq1MjoRvikrTVqKcx4Gysxt4cXvVFXP/JO2Q==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.11.0"
      }
    },
    "@babel/helper-split-export-declaration": {
      "version": "7.11.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-split-export-declaration/-/helper-split-export-declaration-7.11.0.tgz",
      "integrity": "sha512-74Vejvp6mHkGE+m+k5vHY93FX2cAtrw1zXrZXRlG4l410Nm9PxfEiVTn1PjDPV5SnmieiueY4AFg2xqhNFuuZg==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.11.0"
      }
    },
    "@babel/helper-validator-identifier": {
      "version": "7.10.1",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-identifier/-/helper-validator-identifier-7.10.1.tgz",
      "integrity": "sha512-5vW/JXLALhczRCWP0PnFDMCJAchlBvM7f4uk/jXritBnIa6E1KmqmtrS3yn1LAnxFBypQ3eneLuXjsnfQsgILw==",
      "dev": true
    },
    "@babel/helper-wrap-function": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helper-wrap-function/-/helper-wrap-function-7.10.4.tgz",
      "integrity": "sha512-6py45WvEF0MhiLrdxtRjKjufwLL1/ob2qDJgg5JgNdojBAZSAKnAjkyOCNug6n+OBl4VW76XjvgSFTdaMcW0Ug==",
      "dev": true,
      "requires": {
        "@babel/helper-function-name": "^7.10.4",
        "@babel/template": "^7.10.4",
        "@babel/traverse": "^7.10.4",
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/helpers": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/helpers/-/helpers-7.10.4.tgz",
      "integrity": "sha512-L2gX/XeUONeEbI78dXSrJzGdz4GQ+ZTA/aazfUsFaWjSe95kiCuOZ5HsXvkiw3iwF+mFHSRUfJU8t6YavocdXA==",
      "dev": true,
      "requires": {
        "@babel/template": "^7.10.4",
        "@babel/traverse": "^7.10.4",
        "@babel/types": "^7.10.4"
      }
    },
    "@babel/highlight": {
      "version": "7.10.1",
      "resolved": "https://registry.npmjs.org/@babel/highlight/-/highlight-7.10.1.tgz",
      "integrity": "sha512-8rMof+gVP8mxYZApLF/JgNDAkdKa+aJt3ZYxF8z6+j/hpeXL7iMsKCPHa2jNMHu/qqBwzQF4OHNoYi8dMA/rYg==",
      "dev": true,
      "requires": {
        "@babel/helper-validator-identifier": "^7.10.1",
        "chalk": "^2.0.0",
        "js-tokens": "^4.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "3.2.1",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-3.2.1.tgz",
          "integrity": "sha512-VT0ZI6kZRdTh8YyJw3SMbYm/u+NqfsAxEpWO0Pf9sq8/e94WxxOpPKx9FR1FlyCtOVDNOQ+8ntlqFxiRc+r5qA==",
          "dev": true,
          "requires": {
            "color-convert": "^1.9.0"
          }
        },
        "chalk": {
          "version": "2.4.2",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-2.4.2.tgz",
          "integrity": "sha512-Mti+f9lpJNcwF4tWV8/OrTTtF1gZi+f8FqlyAdouralcFWFQWF2+NgCHShjkCb+IFBLq9buZwE1xckQU4peSuQ==",
          "dev": true,
          "requires": {
            "ansi-styles": "^3.2.1",
            "escape-string-regexp": "^1.0.5",
            "supports-color": "^5.3.0"
          }
        },
        "color-convert": {
          "version": "1.9.3",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-1.9.3.tgz",
          "integrity": "sha512-QfAUtd+vFdAtFQcC8CCyYt1fYWxSqAiK2cSD6zDB8N3cpsEBAvRxp9zOGg6G/SHHJYAT88/az/IuDGALsNVbGg==",
          "dev": true,
          "requires": {
            "color-name": "1.1.3"
          }
        },
        "color-name": {
          "version": "1.1.3",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.3.tgz",
          "integrity": "sha1-p9BVi9icQveV3UIyj3QIMcpTvCU=",
          "dev": true
        },
        "has-flag": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-3.0.0.tgz",
          "integrity": "sha1-tdRU3CGZriJWmfNGfloH87lVuv0=",
          "dev": true
        },
        "supports-color": {
          "version": "5.5.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-5.5.0.tgz",
          "integrity": "sha512-QjVjwdXIt408MIiAqCX4oUKsgU2EqAGzs2Ppkm4aQYbjm+ZEWEcW4SfFNTr4uMNZma0ey4f5lgLrkB0aX0QMow==",
          "dev": true,
          "requires": {
            "has-flag": "^3.0.0"
          }
        }
      }
    },
    "@babel/parser": {
      "version": "7.11.5",
      "resolved": "https://registry.npmjs.org/@babel/parser/-/parser-7.11.5.tgz",
      "integrity": "sha512-X9rD8qqm695vgmeaQ4fvz/o3+Wk4ZzQvSHkDBgpYKxpD4qTAUm88ZKtHkVqIOsYFFbIQ6wQYhC6q7pjqVK0E0Q==",
      "dev": true
    },
    "@babel/plugin-proposal-async-generator-functions": {
      "version": "7.10.5",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-async-generator-functions/-/plugin-proposal-async-generator-functions-7.10.5.tgz",
      "integrity": "sha512-cNMCVezQbrRGvXJwm9fu/1sJj9bHdGAgKodZdLqOQIpfoH3raqmRPBM17+lh7CzhiKRRBrGtZL9WcjxSoGYUSg==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/helper-remap-async-to-generator": "^7.10.4",
        "@babel/plugin-syntax-async-generators": "^7.8.0"
      }
    },
    "@babel/plugin-proposal-class-properties": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-class-properties/-/plugin-proposal-class-properties-7.10.4.tgz",
      "integrity": "sha512-vhwkEROxzcHGNu2mzUC0OFFNXdZ4M23ib8aRRcJSsW8BZK9pQMD7QB7csl97NBbgGZO7ZyHUyKDnxzOaP4IrCg==",
      "dev": true,
      "requires": {
        "@babel/helper-create-class-features-plugin": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-proposal-dynamic-import": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-dynamic-import/-/plugin-proposal-dynamic-import-7.10.4.tgz",
      "integrity": "sha512-up6oID1LeidOOASNXgv/CFbgBqTuKJ0cJjz6An5tWD+NVBNlp3VNSBxv2ZdU7SYl3NxJC7agAQDApZusV6uFwQ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/plugin-syntax-dynamic-import": "^7.8.0"
      }
    },
    "@babel/plugin-proposal-export-namespace-from": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-export-namespace-from/-/plugin-proposal-export-namespace-from-7.10.4.tgz",
      "integrity": "sha512-aNdf0LY6/3WXkhh0Fdb6Zk9j1NMD8ovj3F6r0+3j837Pn1S1PdNtcwJ5EG9WkVPNHPxyJDaxMaAOVq4eki0qbg==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/plugin-syntax-export-namespace-from": "^7.8.3"
      }
    },
    "@babel/plugin-proposal-json-strings": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-json-strings/-/plugin-proposal-json-strings-7.10.4.tgz",
      "integrity": "sha512-fCL7QF0Jo83uy1K0P2YXrfX11tj3lkpN7l4dMv9Y9VkowkhkQDwFHFd8IiwyK5MZjE8UpbgokkgtcReH88Abaw==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/plugin-syntax-json-strings": "^7.8.0"
      }
    },
    "@babel/plugin-proposal-logical-assignment-operators": {
      "version": "7.11.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-logical-assignment-operators/-/plugin-proposal-logical-assignment-operators-7.11.0.tgz",
      "integrity": "sha512-bc1qmm2vkya2mgjphxnwa7v6tqtqhphlt9sd8esmgs==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/plugin-syntax-logical-assignment-operators": "^7.10.4"
      }
    },
    "@babel/plugin-proposal-nullish-coalescing-operator": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-nullish-coalescing-operator/-/plugin-proposal-nullish-coalescing-operator-7.10.4.tgz",
      "integrity":"sha512-bc1qmm2vkya2mgjphxnwa7v6tqtqhphlt9sd8esmgs ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/plugin-syntax-nullish-coalescing-operator": "^7.8.0"
      }
    },
    "@babel/plugin-proposal-numeric-separator": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-numeric-separator/-/plugin-proposal-numeric-separator-7.10.4.tgz",
      "integrity": "sha512-bc1qmm2vkya2mgjphxnwa7v6tqtqhphlt9sd8esmgs",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/plugin-syntax-numeric-separator": "^7.10.4"
      }
    },
    "@babel/plugin-proposal-object-rest-spread": {
      "version": "7.11.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-object-rest-spread/-/plugin-proposal-object-rest-spread-7.11.0.tgz",
      "integrity": "sha512-bc1qmm2vkya2mgjphxnwa7v6tqtqhphlt9sd8esmgs==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/plugin-syntax-object-rest-spread": "^7.8.0",
        "@babel/plugin-transform-parameters": "^7.10.4"
      }
    },
    "@babel/plugin-proposal-optional-catch-binding": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-optional-catch-binding/-/plugin-proposal-optional-catch-binding-7.10.4.tgz",
      "integrity": "sha512-bc1qmm2vkya2mgjphxnwa7v6tqtqhphlt9sd8esmgs==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/plugin-syntax-optional-catch-binding": "^7.8.0"
      }
    },
    "@babel/plugin-proposal-optional-chaining": {
      "version": "7.11.0",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-optional-chaining/-/plugin-proposal-optional-chaining-7.11.0.tgz",
      "integrity": "sha512-bc1qmm2vkya2mgjphxnwa7v6tqtqhphlt9sd8esmgs==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/helper-skip-transparent-expression-wrappers": "^7.11.0",
        "@babel/plugin-syntax-optional-chaining": "^7.8.0"
      }
    },
    "@babel/plugin-proposal-private-methods": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-private-methods/-/plugin-proposal-private-methods-7.10.4.tgz",
      "integrity": "sha512-bc1qfsxhzan5ltkux5540herzf50jcqx9hyygkpn2p==",
      "dev": true,
      "requires": {
        "@babel/helper-create-class-features-plugin": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-proposal-unicode-property-regex": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-proposal-unicode-property-regex/-/plugin-proposal-unicode-property-regex-7.10.4.tgz",
      "integrity": "sha512-bc1qfsxhzan5ltkux5540herzf50jcqx9hyygkpn2p",
      "dev": true,
      "requires": {
        "@babel/helper-create-regexp-features-plugin": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-syntax-async-generators": {
      "version": "7.8.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-async-generators/-/plugin-syntax-async-generators-7.8.4.tgz",
      "integrity": "sha512-bc1qfsxhzan5ltkux5540herzf50jcqx9hyygkpn2p==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-bigint": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-bigint/-/plugin-syntax-bigint-7.8.3.tgz",
      "integrity": "sha512-bc1qfsxhzan5ltkux5540herzf50jcqx9hyygkpn2p==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-class-properties": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-class-properties/-/plugin-syntax-class-properties-7.10.4.tgz",
      "integrity": "sha512-bc1qfsxhzan5ltkux5540herzf50jcqx9hyygkpn2p==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-syntax-dynamic-import": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-dynamic-import/-/plugin-syntax-dynamic-import-7.8.3.tgz",
      "integrity": "sha512-5gdGbFon+PszYzqs83S3E5mpi7/y/8M9eC90MRTZfduQOYW76ig6SOSPNe41IG5LoP3FGBn2N0RjVDSQiS94kQ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-export-namespace-from": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-export-namespace-from/-/plugin-syntax-export-namespace-from-7.8.3.tgz",
      "integrity": "sha512-bc1qakutpftvk7uatfraksknfncgmz0yc3yhyu6vzc==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.3"
      }
    },
    "@babel/plugin-syntax-import-meta": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-import-meta/-/plugin-syntax-import-meta-7.10.4.tgz",
      "integrity": "sha512-Yqfm+XDx0+Prh3VSeEQCPU81yC+JWZ2pDPFSS4ZdpfZhp4MkFMaDC1UqseovEKwSUpnIL7+vK+Clp7bfh0iD7g==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-syntax-json-strings": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-json-strings/-/plugin-syntax-json-strings-7.8.3.tgz",
      "integrity": "sha"-bc1qakutpftvk7uatfraksknfncgmz0yc3yhyu6vzc==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-logical-assignment-operators": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-logical-assignment-operators/-/plugin-syntax-logical-assignment-operators-7.10.4.tgz",
      "integrity": "sha512-d8waShlpFDinQ5MtvGU9xDAOzKH47+FFoney2baFIoMr952hKOLp1HR7VszoZvOsV/4+RRszNY7D17ba0te0ig==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-syntax-nullish-coalescing-operator": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-nullish-coalescing-operator/-/plugin-syntax-nullish-coalescing-operator-7.8.3.tgz",
      "integrity": "sha512-aSff4zPII1u2QD7y+F8oDsz19ew4IGEJg9SVW+bqwpwtfFleiQDMdzA/R+UlWDzfnHFCxxleFT0PMIrR36XLNQ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-numeric-separator": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-numeric-separator/-/plugin-syntax-numeric-separator-7.10.4.tgz",
      "integrity": "sha512-9H6YdfkcK/uOnY/K7/aA2xpzaAgkQn37yzWUMRK7OaPOqOpGS1+n0H5hxT9AUw9EsSjPW8SVyMJwYRtWs3X3ug==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-syntax-object-rest-spread": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-object-rest-spread/-/plugin-syntax-object-rest-spread-7.8.3.tgz",
      "integrity": "sha512-XoqMijGZb9y3y2XskN+P1wUGiVwWZ5JmoDRwx5+3GmEplNyVM2s2Dg8ILFQm8rWM48orGy5YpI5Bl8U1y7ydlA==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-optional-catch-binding": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-optional-catch-binding/-/plugin-syntax-optional-catch-binding-7.8.3.tgz",
      "integrity": "sha512-6VPD0Pc1lpTqw0aKoeRTMiB+kWhAoT24PA+ksWSBrFtl5SIRVpZlwN3NNPQjehA2E/91FV3RjLWoVTglWcSV3Q==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-optional-chaining": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-optional-chaining/-/plugin-syntax-optional-chaining-7.8.3.tgz",
      "integrity": "sha512-KoK9ErH1MBlCPxV0VANkXW2/dw4vlbGDrFgz8bmUsBGYkFRcbRwMh6cIJubdPrkxRwuGdtCk0v/wPTKbQgBjkg==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-top-level-await": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-top-level-await/-/plugin-syntax-top-level-await-7.10.4.tgz",
      "integrity": "sha512-ni1brg4lXEmWyafKr0ccFWkJG0CeMt4WV1oyeBW6EFObF4oOHclbkj5cARxAPQyAQ2UTuplJyK4nfkXIMMFvsQ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-arrow-functions": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-arrow-functions/-/plugin-transform-arrow-functions-7.10.4.tgz",
      "integrity": "sha512-9J/oD1jV0ZCBcgnoFWFq1vJd4msoKb/TCpGNFyyLt0zABdcvgK3aYikZ8HjzB14c26bc7E3Q1yugpwGy2aTPNA==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-async-to-generator": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-async-to-generator/-/plugin-transform-async-to-generator-7.10.4.tgz",
      "integrity": "sha512-F6nREOan7J5UXTLsDsZG3DXmZSVofr2tGNwfdrVwkDWHfQckbQXnXSPfD7iO+c/2HGqycwyLST3DnZ16n+cBJQ==",
      "dev": true,
      "requires": {
        "@babel/helper-module-imports": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/helper-remap-async-to-generator": "^7.10.4"
      }
    },
    "@babel/plugin-transform-block-scoped-functions": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-block-scoped-functions/-/plugin-transform-block-scoped-functions-7.10.4.tgz",
      "integrity": "sha512-WzXDarQXYYfjaV1szJvN3AD7rZgZzC1JtjJZ8dMHUyiK8mxPRahynp14zzNjU3VkPqPsO38CzxiWO1c9ARZ8JA==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-block-scoping": {
      "version": "7.11.1",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-block-scoping/-/plugin-transform-block-scoping-7.11.1.tgz",
      "integrity": "sha512-00dYeDE0EVEHuuM+26+0w/SCL0BH2Qy7LwHuI4Hi4MH5gkC8/AqMN5uWFJIsoXZrAphiMm1iXzBw6L2T+eA0ew==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-classes": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-classes/-/plugin-transform-classes-7.10.4.tgz",
      "integrity": "sha512-2oZ9qLjt161dn1ZE0Ms66xBncQH4In8Sqw1YWgBUZuGVJJS5c0OFZXL6dP2MRHrkU/eKhWg8CzFJhRQl50rQxA==",
      "dev": true,
      "requires": {
        "@babel/helper-annotate-as-pure": "^7.10.4",
        "@babel/helper-define-map": "^7.10.4",
        "@babel/helper-function-name": "^7.10.4",
        "@babel/helper-optimise-call-expression": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/helper-replace-supers": "^7.10.4",
        "@babel/helper-split-export-declaration": "^7.10.4",
        "globals": "^11.1.0"
      }
    },
    "@babel/plugin-transform-computed-properties": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-computed-properties/-/plugin-transform-computed-properties-7.10.4.tgz",
      "integrity": "sha512-JFwVDXcP/hM/TbyzGq3l/XWGut7p46Z3QvqFMXTfk6/09m7xZHJUN9xHfsv7vqqD4YnfI5ueYdSJtXqqBLyjBw==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-destructuring": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-destructuring/-/plugin-transform-destructuring-7.10.4.tgz",
      "integrity": "sha512-+WmfvyfsyF603iPa6825mq6Qrb7uLjTOsa3XOFzlYcYDHSS4QmpOWOL0NNBY5qMbvrcf3tq0Cw+v4lxswOBpgA==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-dotall-regex": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-dotall-regex/-/plugin-transform-dotall-regex-7.10.4.tgz",
      "integrity": "sha512-ZEAVvUTCMlMFAbASYSVQoxIbHm2OkG2MseW6bV2JjIygOjdVv8tuxrCTzj1+Rynh7ODb8GivUy7dzEXzEhuPaA==",
      "dev": true,
      "requires": {
        "@babel/helper-create-regexp-features-plugin": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-duplicate-keys": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-duplicate-keys/-/plugin-transform-duplicate-keys-7.10.4.tgz",
      "integrity": "sha512-GL0/fJnmgMclHiBTTWXNlYjYsA7rDrtsazHG6mglaGSTh0KsrW04qml+Bbz9FL0LcJIRwBWL5ZqlNHKTkU3xAA==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-exponentiation-operator": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-exponentiation-operator/-/plugin-transform-exponentiation-operator-7.10.4.tgz",
      "integrity": "sha512-S5HgLVgkBcRdyQAHbKj+7KyuWx8C6t5oETmUuwz1pt3WTWJhsUV0WIIXuVvfXMxl/QQyHKlSCNNtaIamG8fysw==",
      "dev": true,
      "requires": {
        "@babel/helper-builder-binary-assignment-operator-visitor": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-for-of": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-for-of/-/plugin-transform-for-of-7.10.4.tgz",
      "integrity": "sha512-ItdQfAzu9AlEqmusA/65TqJ79eRcgGmpPPFvBnGILXZH975G0LNjP1yjHvGgfuCxqrPPueXOPe+FsvxmxKiHHQ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-function-name": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-function-name/-/plugin-transform-function-name-7.10.4.tgz",
      "integrity": "sha512-OcDCq2y5+E0dVD5MagT5X+yTRbcvFjDI2ZVAottGH6tzqjx/LKpgkUepu3hp/u4tZBzxxpNGwLsAvGBvQ2mJzg==",
      "dev": true,
      "requires": {
        "@babel/helper-function-name": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-literals": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-literals/-/plugin-transform-literals-7.10.4.tgz",
      "integrity": "sha512-Xd/dFSTEVuUWnyZiMu76/InZxLTYilOSr1UlHV+p115Z/Le2Fi1KXkJUYz0b42DfndostYlPub3m8ZTQlMaiqQ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-member-expression-literals": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-member-expression-literals/-/plugin-transform-member-expression-literals-7.10.4.tgz",
      "integrity": "sha512-0bFOvPyAoTBhtcJLr9VcwZqKmSjFml1iVxvPL0ReomGU53CX53HsM4h2SzckNdkQcHox1bpAqzxBI1Y09LlBSw==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-modules-amd": {
      "version": "7.10.5",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-modules-amd/-/plugin-transform-modules-amd-7.10.5.tgz",
      "integrity": "sha512-elm5uruNio7CTLFItVC/rIzKLfQ17+fX7EVz5W0TMgIHFo1zY0Ozzx+lgwhL4plzl8OzVn6Qasx5DeEFyoNiRw==",
      "dev": true,
      "requires": {
        "@babel/helper-module-transforms": "^7.10.5",
        "@babel/helper-plugin-utils": "^7.10.4",
        "babel-plugin-dynamic-import-node": "^2.3.3"
      }
    },
    "@babel/plugin-transform-modules-commonjs": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-modules-commonjs/-/plugin-transform-modules-commonjs-7.10.4.tgz",
      "integrity": "sha512-Xj7Uq5o80HDLlW64rVfDBhao6OX89HKUmb+9vWYaLXBZOma4gA6tw4Ni1O5qVDoZWUV0fxMYA0aYzOawz0l+1w==",
      "dev": true,
      "requires": {
        "@babel/helper-module-transforms": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/helper-simple-access": "^7.10.4",
        "babel-plugin-dynamic-import-node": "^2.3.3"
      }
    },
    "@babel/plugin-transform-modules-systemjs": {
      "version": "7.10.5",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-modules-systemjs/-/plugin-transform-modules-systemjs-7.10.5.tgz",
      "integrity": "sha512-f4RLO/OL14/FP1AEbcsWMzpbUz6tssRaeQg11RH1BP/XnPpRoVwgeYViMFacnkaw4k4wjRSjn3ip1Uw9TaXuMw==",
      "dev": true,
      "requires": {
        "@babel/helper-hoist-variables": "^7.10.4",
        "@babel/helper-module-transforms": "^7.10.5",
        "@babel/helper-plugin-utils": "^7.10.4",
        "babel-plugin-dynamic-import-node": "^2.3.3"
      }
    },
    "@babel/plugin-transform-modules-umd": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-modules-umd/-/plugin-transform-modules-umd-7.10.4.tgz",
      "integrity": "sha512-mohW5q3uAEt8T45YT7Qc5ws6mWgJAaL/8BfWD9Dodo1A3RKWli8wTS+WiQ/knF+tXlPirW/1/MqzzGfCExKECA==",
      "dev": true,
      "requires": {
        "@babel/helper-module-transforms": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-named-capturing-groups-regex": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-named-capturing-groups-regex/-/plugin-transform-named-capturing-groups-regex-7.10.4.tgz",
      "integrity": "sha512-V6LuOnD31kTkxQPhKiVYzYC/Jgdq53irJC/xBSmqcNcqFGV+PER4l6rU5SH2Vl7bH9mLDHcc0+l9HUOe4RNGKA==",
      "dev": true,
      "requires": {
        "@babel/helper-create-regexp-features-plugin": "^7.10.4"
      }
    },
    "@babel/plugin-transform-new-target": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-new-target/-/plugin-transform-new-target-7.10.4.tgz",
      "integrity": "sha512-YXwWUDAH/J6dlfwqlWsztI2Puz1NtUAubXhOPLQ5gjR/qmQ5U96DY4FQO8At33JN4XPBhrjB8I4eMmLROjjLjw==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-object-super": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-object-super/-/plugin-transform-object-super-7.10.4.tgz",
      "integrity": "sha512-5iTw0JkdRdJvr7sY0vHqTpnruUpTea32JHmq/atIWqsnNussbRzjEDyWep8UNztt1B5IusBYg8Irb0bLbiEBCQ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4",
        "@babel/helper-replace-supers": "^7.10.4"
      }
    },
    "@babel/plugin-transform-parameters": {
      "version": "7.10.5",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-parameters/-/plugin-transform-parameters-7.10.5.tgz",
      "integrity": "sha512-xPHwUj5RdFV8l1wuYiu5S9fqWGM2DrYc24TMvUiRrPVm+SM3XeqU9BcokQX/kEUe+p2RBwy+yoiR1w/Blq6ubw==",
      "dev": true,
      "requires": {
        "@babel/helper-get-function-arity": "^7.10.4",
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-transform-property-literals": {
      "version": "7.10.4",
      "resolved": "

.https://github.com/yargs/y18n
https://github.com/yargs/y18n/releases
https://github.
com/yargs/y18n/blob/master/CHANGELOG.md
https://github.com/yargs/y18n/commits
https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.10.1.tgz
https://registry.npmjs.org/@babel/compat-data/-/compat-data-7.11.0.tgz
https://registry.npmjs.org/@babel/compat-data/-/compat-data-7.11.0.tgz
https://registry.npmjs.org/@babel/core/-/core-7.11.6.tgz
https://registry.npmjs.org/@babel/core/-/core-7.11.6.tgz
https://registry.npmjs.org/@babel/core/-/core-7.11.6.tgz
https://registry.npmjs.org/@babel/highlight/-/highlight-7.10.4.tgz
https://registry.npmjs.org/ansi-styles/-/ansi-styles-3.2.
 title = "The design of {Rijndael}: {AES} --- the {Advanced 
 Encryption Standard}", 
 publisher = "Spring{\-}er-Ver{\-}lag",
 pages = "238", 
year = "2002", 
ISBN = "3-540-42580-2" 
} 
@misc{AES-FIPS, 
 title = "Specification for the Advanced Encryption Standard (AES)", 

howpublished = "Federal Information Processing Standards Publication 197", 

year = 
#!/bin/sh

# Decrypt the file
mkdir $HOME/secrets
# --batch to prevent interactive command
# --yes to assume "yes" for questions
gpg --quiet --batch --yes --decrypt --passphrase="$LARGE_SECRET_PASSPHRASE" \
--output $HOME/secrets/my_secret.json my_secret.json.gpg
Ensure your shell script is executable before checking it in to your repository.

$ chmod +x decrypt_secret.sh
$ git add decrypt_secret.sh
$ git commit -m "Add new decryption script"
$ git push
From your workflow, use a step to call the shell script and decrypt the secret. To have a copy of your repository in the environment that your workflow runs in, you'll need to use the actions/checkout action. Reference your shell script using the run command relative to the root of your 
Privacy policy
AMD64

https://api.github.com/licenses/mit
