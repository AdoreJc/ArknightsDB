# EnemyDuelProtocolRetCode

**Namespace:** `Torappu.UI.EnemyDuel.Service.Mode.Multi`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | OK |

| 101 | SceneNotExist |

| 102 | SceneJoinFailed |

| 601 | TeamNotExist |

| 602 | TeamJoinFailed |

| 603 | TeamSceneStartFailed |

| 604 | TeamFull |

| 605 | TeamSceneStartFailedFull |

| 901 | ClientCodeNetLost |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service.Mode.Multi
public enum EnemyDuelProtocolRetCode
{
	public Int32 value__; // 0x10
	public const EnemyDuelProtocolRetCode OK = 0; // 0x0
	public const EnemyDuelProtocolRetCode SceneNotExist = 101; // 0x0
	public const EnemyDuelProtocolRetCode SceneJoinFailed = 102; // 0x0
	public const EnemyDuelProtocolRetCode TeamNotExist = 601; // 0x0
	public const EnemyDuelProtocolRetCode TeamJoinFailed = 602; // 0x0
	public const EnemyDuelProtocolRetCode TeamSceneStartFailed = 603; // 0x0
	public const EnemyDuelProtocolRetCode TeamFull = 604; // 0x0
	public const EnemyDuelProtocolRetCode TeamSceneStartFailedFull = 605; // 0x0
	public const EnemyDuelProtocolRetCode ClientCodeNetLost = 901; // 0x0


}
```