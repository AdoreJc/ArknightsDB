# SandboxV2AdminSelectListView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Transform _leftContainer`

- `Transform _adatperContainer`

- `SandboxV2AdminCharSelectAbstractLeftView m_leftView`

- `Transform _shuffleContainer`

- `Transform _ensureContainer`

- `Transform _popContainer`

- `GameObject _noCharPrefab`

- `SandboxV2AdminCharSelectStateMode m_charSelectMode`

- `SandboxV2AdminCharAbstractShuffleView m_shuffleView`

- `SandboxV2AdminCharAbstractEnsureView m_ensureView`

- `SandboxV2AdminCharSelectAbstractPopView m_popView`

- `SandboxV2AdminCharSelectRecycleAdapter m_recycleAdapter`

- `SandboxV2CharSelectCharCardType m_cardType`

- `SandboxV2AdminCharSelectStateMode m_cacheMode`

- `UIStateFinder m_stateFinder`

- `Int32 m_focusSeq`


## Methods

- `Void InitWithHolder(SandboxV2AdminCharSelectStateMode, ILoadAsset)`

- `Void FocusOnInit(Int32, Int32)`

- `Void _TryToSwitchPopView(SandboxV2CharListViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminSelectListView : DataBinder`1, IHotfixable
{
	private Transform _leftContainer; // 0x20
	private Transform _adatperContainer; // 0x28
	private SandboxV2AdminCharSelectAbstractLeftView m_leftView; // 0x30
	private Transform _shuffleContainer; // 0x38
	private Transform _ensureContainer; // 0x40
	private Transform _popContainer; // 0x48
	private GameObject _noCharPrefab; // 0x50
	private SandboxV2AdminCharSelectStateMode m_charSelectMode; // 0x58
	private SandboxV2AdminCharAbstractShuffleView m_shuffleView; // 0x60
	private SandboxV2AdminCharAbstractEnsureView m_ensureView; // 0x68
	private SandboxV2AdminCharSelectAbstractPopView m_popView; // 0x70
	private SandboxV2AdminCharSelectRecycleAdapter m_recycleAdapter; // 0x78
	private SandboxV2CharSelectCharCardType m_cardType; // 0x80
	private SandboxV2AdminCharSelectStateMode m_cacheMode; // 0x84
	private UIStateFinder m_stateFinder; // 0x88
	private const Int32 VER_LINE_PER; // 0x0
	private const Int32 ADAPTER_START; // 0x0
	private Int32 m_focusSeq; // 0x98
	private static DelegateBridge __Hotfix0_InitWithHolder; // 0x0
	private static DelegateBridge __Hotfix0_FocusOnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__TryToSwitchPopView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x24aec3c VA: 0x7594ac6c3c
	public Void InitWithHolder(SandboxV2AdminCharSelectStateMode mode, ILoadAsset loadAsset) { }
	// RVA: 0x24b0974 VA: 0x7594ac8974
	public Void FocusOnInit(Int32 focusIndex, Int32 allCount) { }
	// RVA: 0x24b0ac0 VA: 0x7594ac8ac0
	public override Void OnValueChanged(SandboxV2CharListProperty property) { }
	// RVA: 0x24b1014 VA: 0x7594ac9014
	private Void _TryToSwitchPopView(SandboxV2CharListViewModel charListViewModel, Boolean isShow) { }
	// RVA: 0x24b1308 VA: 0x7594ac9308
	public Void .ctor() { }
}
```