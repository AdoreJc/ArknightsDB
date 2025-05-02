# BuildingCharCtrlHomeViewModel

**Namespace:** `Torappu.Building.UI`


## Fields

- `Boolean isShowUI`

- `Boolean interactable`

- `Boolean isInteracting`

- `Boolean canGoUpstairs`

- `Boolean inElevatorRoom`

- `Boolean canGoDownstairs`

- `Boolean isUpDownstairs`

- `Boolean isGoingUp`

- `Boolean isGoingDown`

- `Boolean showEmoji`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingCharCtrlHomeViewModel : IHotfixable
{
	public const String EMOJI_ACTION_ID; // 0x0
	public Boolean isShowUI; // 0x10
	public Boolean interactable; // 0x11
	public Boolean isInteracting; // 0x12
	public Boolean canGoUpstairs; // 0x13
	public Boolean inElevatorRoom; // 0x14
	public Boolean canGoDownstairs; // 0x15
	public Boolean isUpDownstairs; // 0x16
	public Boolean isGoingUp; // 0x17
	public Boolean isGoingDown; // 0x18
	public Boolean showEmoji; // 0x19
	public List`1 emojiList; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3d341e0 VA: 0x759634c1e0
	public Void LoadData() { }
	// RVA: 0x3d345a8 VA: 0x759634c5a8
	public Void .ctor() { }
}
```