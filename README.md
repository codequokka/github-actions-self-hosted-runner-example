# github-actions-self-hosted-runner-example
```
❯ export GITHUB_ACCESS_TOKEN=<your-github-access-token>

❯ docker compose up -d
[+] Running 9/9
 ✔ my_runner 8 layers [⣿⣿⣿⣿⣿⣿⣿⣿]      0B/0B      Pulled                                                              105.7s    ✔ edaedc954fb5 Pull complete                                                                                       15.6s    ✔ 13e0351bd78e Pull complete                                                                                       98.5s    ✔ 8fc7a35e3bfe Pull complete                                                                                       98.6s    ✔ e313b726c9ee Pull complete                                                                                       98.6s    ✔ 6e667c4412db Pull complete                                                                                       98.6s    ✔ 0c24ca779a73 Pull complete                                                                                      102.1s    ✔ 1e688a3c61b5 Pull complete                                                                                      102.1s    ✔ 8d6f4afee590 Pull complete                                                                                      102.2s [+] Running 2/2
 ✔ Network github-actions-self-hosted-runner-example_default        Created                                            0.1s  ✔ Container github-actions-self-hosted-runner-example-my_runner-1  Started                                            0.9s

❯ docker ps
CONTAINER ID   IMAGE                    COMMAND                  CREATED          STATUS          PORTS     NAMES
d44cf1838bc4   myoung34/github-runner   "/entrypoint.sh ./bi…"   15 seconds ago   Up 14 seconds             github-actions-self-hosted-runner-example-my_runner-1
```
