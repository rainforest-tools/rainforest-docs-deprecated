# Commit Message

```text
[STATE] Message...
```

| STATE | Description |
| :--- | :--- |
| ORPHAN\_CHECKOUT | commit right after `git checkout --orphan <BRANCH_NAME>` |
| ADD | Add features |
| UPDATE | Update features |
| WIP | Work in progress |

> **Don't commit multiple changes in one commit!**

### Submodule

```text
[SUBMODULE_NAME] STATE - Message...
```

* SUBMODULE\_NAME: name of submodule
* STATE:

| STATE | Description |
| :--- | :--- |
| ADD | add new submodule |
| UPDATE | update submodule |
| DELETE | delete submodule |

### Group

```text
[GROUP] STATE - Message...
```

* Please refer to [Submodule](commit-message.md#submodule)

