# UICharacterProfessionFilterHolder

**Namespace:** `Torappu.UI`


## Fields

- `UICharacterProfessionFilterView _filterView`

- `UICharacterProfessionFilterProperty m_prop`


## Methods

- `Void ApplyInvalidSubProf(HashSet`1)`

- `Void _ApplyData()`

- `Void _OnBarTopClick()`

- `Void _OnProfessionClick(ProfessionCategory, Boolean)`

- `Void _OnSubProfessionClick(String, Boolean)`

- `Void _OnCloseSubProfPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterProfessionFilterHolder : UICharacterFilterHolder, IHotfixable
{
	private UICharacterProfessionFilterView _filterView; // 0x28
	private UICharacterProfessionFilterProperty m_prop; // 0x30
	private static DelegateBridge __Hotfix0_ApplyInvalidSubProf; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0__ApplyData; // 0x10
	private static DelegateBridge __Hotfix0__OnBarTopClick; // 0x18
	private static DelegateBridge __Hotfix0__OnProfessionClick; // 0x20
	private static DelegateBridge __Hotfix0__OnSubProfessionClick; // 0x28
	private static DelegateBridge __Hotfix0__OnCloseSubProfPanel; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2123e18 VA: 0x759473be18
	public Void ApplyInvalidSubProf(HashSet`1 invalidSubProfs) { }
	// RVA: 0x21240e0 VA: 0x759473c0e0
	protected override Void OnCreate() { }
	// RVA: 0x21243f0 VA: 0x759473c3f0
	private Void _ApplyData() { }
	// RVA: 0x21246f8 VA: 0x759473c6f8
	private Void _OnBarTopClick() { }
	// RVA: 0x21248a8 VA: 0x759473c8a8
	private Void _OnProfessionClick(ProfessionCategory profession, Boolean isAll) { }
	// RVA: 0x2124af4 VA: 0x759473caf4
	private Void _OnSubProfessionClick(String subProfId, Boolean isAll) { }
	// RVA: 0x2124c0c VA: 0x759473cc0c
	private Void _OnCloseSubProfPanel() { }
	// RVA: 0x2124cdc VA: 0x759473ccdc
	public Void .ctor() { }
}
```