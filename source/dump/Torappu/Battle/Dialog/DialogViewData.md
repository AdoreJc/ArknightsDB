# DialogViewData

**Namespace:** `Torappu.Battle.Dialog`


## Fields

- `String name`

- `String avatarId`

- `String content`

- `Boolean isAvatarRight`

- `Single delay`

- `BattleDialogType dialogType`

- `Int32 commandIndex`

- `String commandKey`


## Methods

- `Void Reset()`

- `Boolean IsFilled(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogViewData : IHotfixable
{
	public static readonly DialogViewData DEFAULT; // 0x0
	public String name; // 0x10
	public String avatarId; // 0x18
	public String content; // 0x20
	public Boolean isAvatarRight; // 0x28
	public List`1 dialogOptions; // 0x30
	public Single delay; // 0x38
	public BattleDialogType dialogType; // 0x3c
	public Int32 commandIndex; // 0x40
	public String commandKey; // 0x48
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_IsFilled; // 0x18


	// RVA: 0x1d20a24 VA: 0x7594338a24
	public Void Reset() { }
	// RVA: 0x1d20bcc VA: 0x7594338bcc
	public Void .ctor() { }
	// RVA: 0x1d20c54 VA: 0x7594338c54
	public Boolean IsFilled(Boolean isSkip) { }
	// RVA: 0x1d20d3c VA: 0x7594338d3c
	private static Void .cctor() { }
}
```