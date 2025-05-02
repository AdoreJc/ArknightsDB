# SocialUnlockStateBean

**Namespace:** `Torappu.UI.Shop`


## Fields

- `String currentGroupId`

- `Int32 maxLength`

- `Int32 minLength`

- `Single maxPercent`

- `Int32 creditUsed`

- `String creditGroup`


## Methods

- `Boolean _CheckCharUnlock(String)`

- `Void InitGroupId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SocialUnlockStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	private static readonly Single percentMin; // 0x0
	public Dictionary`2 charUnlockState; // 0x18
	public String currentGroupId; // 0x20
	public Dictionary`2 groupList; // 0x28
	public Int32 maxLength; // 0x30
	public Int32 minLength; // 0x34
	public Single maxPercent; // 0x38
	public Int32 creditUsed; // 0x3c
	public String creditGroup; // 0x40
	private Dictionary`2 m_charUnlockCache; // 0x48
	private static DelegateBridge __Hotfix0__CheckCharUnlock; // 0x8
	private static DelegateBridge __Hotfix0_InitGroupId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2471374 VA: 0x7594a89374
	private Boolean _CheckCharUnlock(String charId) { }
	// RVA: 0x2470818 VA: 0x7594a88818
	public Void InitGroupId(String groupId) { }
	// RVA: 0x24714ac VA: 0x7594a894ac
	public Void .ctor() { }
	// RVA: 0x2471580 VA: 0x7594a89580
	private static Void .cctor() { }
}
```