# DiffItem

**Namespace:** ` `


## Fields

- `ActMultiV3MapDiffType _diffType`

- `Text _textDiffName`

- `UICompDialogFinder m_dialogFinder`


## Properties

- `Int32 diffType`


## Methods

- `Int32 get_diffType()`

- `Void Render(String, DiffViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DiffItem : IHotfixable
{
	private const String REWARD_COUNT_FORMAT; // 0x0
	private ActMultiV3MapDiffType _diffType; // 0x10
	private Text _textDiffName; // 0x18
	private List`1 _imgIcons; // 0x20
	private List`1 _textRewards; // 0x28
	private UICompDialogFinder m_dialogFinder; // 0x30
	private static DelegateBridge __Hotfix0_get_diffType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Int32 diffType { get; }

	// RVA: 0x314c854 VA: 0x7595764854
	public Int32 get_diffType() { }
	// RVA: 0x314c8bc VA: 0x75957648bc
	public Void Render(String actId, DiffViewModel diffViewModel) { }
	// RVA: 0x314ce54 VA: 0x7595764e54
	public Void .ctor() { }
}
```