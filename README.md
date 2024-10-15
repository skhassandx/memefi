> [<img src="https://img.shields.io/badge/Telegram-%50Me-orange">]

# Use Node.Js 18 or 50

## Functionality

| Functional                                                     | Supported |
| -------------------------------------------------------------- | :-------: |
| Purchasing TapBot                                              |    ✅     |
| Starting TapBot                                                |    ✅     |
| Claiming TapBot reward every 5 hours                           |    ✅     |
| Claiming Daily Combo                                           |    ✅     |
| Claiming Tasks                                                 |    ✅     |
| Spinning game                                                  |    ✅     |
| User Agent for each session                                    |    ✅     |
| Multithreading                                                 |    ✅     |
| Binding a proxy to a session                                   |    ✅     |
| Auto-purchase of items if you have coins (tap, energy, charge) |    ✅     |
| Random sleep time between clicks                               |    ✅     |
| Random number of clicks per request                            |    ✅     |
| Caching session data                                           |    ✅     |
| Using a session/query_id                                       |    ✅     |
| Binding a proxy to a session/query_id                          |    ✅     |

### [How to add query id] see yt

## [Settings]

| Settings                        | Description                                                                                                     |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| **API_ID / API_HASH**           | Platform data from which to launch a Telegram session (stock - Android)                                         |
| **MIN_AVAILABLE_ENERGY**        | Minimum amount of available energy, upon reaching which there will be a delay (eg 100)                          |
| **AUTO_UPGRADE_DAMAGE**         | Should I improve the tap (True / False)                                                                         |
| **MAX_DAMAGE_LEVEL**            | Maximum level of tap pumping (eg 5)                                                                             |
| **AUTO_UPGRADE_ENERGY**         | Should I improve the tap (True / False)                                                                         |
| **MAX_ENERGY_LEVEL**            | Maximum level of tap pumping (eg 5)                                                                             |
| **AUTO_UPGRADE_RECHARGE**       | Should I improve the tap (True / False)                                                                         |
| **MAX_RECHARGE_LEVEL**          | Maximum level of tap pumping (eg 5)                                                                             |
| **AUTO_APPLY_TURBO**            | Whether to use the daily free energy boost (True / False)                                                       |
| **AUTO_APPLY_ENERGY**           | Whether to use the daily free turbo boost (True / False)                                                        |
| **RANDOM_TAPS**                 | Random number of taps (eg [50,500])                                                                             |
| **RANDOM_TURBO_TAPS**           | Random number of turbo taps (eg [50,500])                                                                       |
| **SLEEP_BETWEEN_REQUESTS**      | Random delay between requests in seconds (eg [10,56])                                                           |
| **DELAY_BETWEEN_TURBO**         | Random delay between turbo taps in seconds (eg [10,56])                                                         |
| **DELAY_BETWEEN_TAPS**          | Random delay between taps in seconds (eg [10,56])                                                               |
| **DELAY_BETWEEN_TASKS**         | Random delay between tasks in seconds (eg [10,56])                                                              |
| **DELAY_BETWEEN_STARTING_BOT**  | Random delay between starting bot (eg [10,56])                                                                  |
| **AUTO_BUY_TAPBOT**             | Whether to purchase tapbot automatically (True / False)                                                         |
| **AUTO_SPIN**                   | Whether to spin automatically (True / False)                                                                    |
| **AUTO_COMPLETE_TASKS**         | Whether to should claim tasks (True / False)                                                                    |
| **AUTO_CLAIM_AND_START_TAPBOT** | Whether the bot should to claim and start tapbot (True / False)                                                 |
| **USE_PROXY_FROM_JS_FILE**      | Whether to use proxy from the `bot/config/proxies.js` file (True / False)                                       |
| **USE_PROXY_FROM_TXT_FILE**     | Whether to use proxy from the `bot/config/proxies.txt` file (True / False)                                      |
| **USE_REGISTRATION_PROXY**      | Whether to use proxy from the `bot/config/registrationProxy.js` file when creating a new session (True / False) |

