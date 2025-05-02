# ActMultiV3MapTypeData

**Namespace:** `Torappu`


## Fields

- `String modeId`

- `ActMultiV3MapModeType mode`

- `ActMultiV3MapDiffType difficulty`

- `Boolean isDefaultSelectInQuickMatch`

- `Int32 squadMax`

- `String matchUnlockModeId`

- `Int32 matchUnlockParam`

- `String unlockHint`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActMultiV3MapTypeData
{
	public String modeId; // 0x10
	public ActMultiV3MapModeType mode; // 0x18
	public ActMultiV3MapDiffType difficulty; // 0x1c
	public Boolean isDefaultSelectInQuickMatch; // 0x20
	public Int32 squadMax; // 0x24
	public String matchUnlockModeId; // 0x28
	public Int32 matchUnlockParam; // 0x30
	public List`1 stageIdInModeList; // 0x38
	public String unlockHint; // 0x40


	// RVA: 0x33bc508 VA: 0x75959d4508
	public Void .ctor() { }
}
```