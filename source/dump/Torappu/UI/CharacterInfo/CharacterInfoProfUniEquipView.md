# CharacterInfoProfUniEquipView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `SimpleLayoutContent _uniequipContent`

- `GameObject _onCurrentPart`

- `GameObject _onSelectPart`

- `UnityEvent _onChangeEquip`

- `UIStringEvent _onSelectEquipEvent`

- `Text _selectedName`

- `Text _equipLevel`

- `Single _equipLimitContentWidth`

- `Single _equipMaxContentWidth`

- `UIWrappedScrollRect _equipScrollRect`

- `RectTransform _equipScrollContentRectTransform`

- `ScrollRect _rightScrollRect`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `Int32 m_sequenceNum`

- `Boolean m_needRefreshScroll`

- `CharViewModel m_viewModel`


## Methods

- `Void _InitIfNot()`

- `Void OnSelectEquip()`

- `Void _OnSelectEquipId(String)`

- `Void _OnRefreshEquipInfo(String)`

- `Void CheckIsNeedRefreshScroll(Int32)`

- `Boolean <>xLuaBaseProxy_CheckAvailInfo(CharViewModel)`

- `Void <>xLuaBaseProxy_Render(CharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoProfUniEquipView : CharacterInfoRightProfObj
{
	private SimpleLayoutContent _uniequipContent; // 0x20
	private GameObject _onCurrentPart; // 0x28
	private GameObject _onSelectPart; // 0x30
	private UnityEvent _onChangeEquip; // 0x38
	private UIStringEvent _onSelectEquipEvent; // 0x40
	private Text _selectedName; // 0x48
	private Text _equipLevel; // 0x50
	private Single _equipLimitContentWidth; // 0x58
	private Single _equipMaxContentWidth; // 0x5c
	private UIWrappedScrollRect _equipScrollRect; // 0x60
	private RectTransform _equipScrollContentRectTransform; // 0x68
	private ScrollRect _rightScrollRect; // 0x70
	private Adapter m_adapter; // 0x78
	private Boolean m_isInited; // 0x80
	private Int32 m_sequenceNum; // 0x84
	private Boolean m_needRefreshScroll; // 0x88
	private CharViewModel m_viewModel; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnSelectEquip; // 0x8
	private static DelegateBridge __Hotfix0_CheckAvailInfo; // 0x10
	private static DelegateBridge __Hotfix0__OnSelectEquipId; // 0x18
	private static DelegateBridge __Hotfix0__OnRefreshEquipInfo; // 0x20
	private static DelegateBridge __Hotfix0_GetAndApplyHeight; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0_CheckIsNeedRefreshScroll; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d85760 VA: 0x759539d760
	private Void _InitIfNot() { }
	// RVA: 0x2d85914 VA: 0x759539d914
	public Void OnSelectEquip() { }
	// RVA: 0x2d85998 VA: 0x759539d998
	public override Boolean CheckAvailInfo(CharViewModel viewModel) { }
	// RVA: 0x2d85a64 VA: 0x759539da64
	private Void _OnSelectEquipId(String equipId) { }
	// RVA: 0x2d85b10 VA: 0x759539db10
	private Void _OnRefreshEquipInfo(String equipId) { }
	// RVA: 0x2d85d70 VA: 0x759539dd70
	public override Single GetAndApplyHeight() { }
	// RVA: 0x2d85dd8 VA: 0x759539ddd8
	public override Void Render(CharViewModel viewModel) { }
	// RVA: 0x2d83864 VA: 0x759539b864
	public Void CheckIsNeedRefreshScroll(Int32 inputSequenceNum) { }
	// RVA: 0x2d85f68 VA: 0x759539df68
	public Void .ctor() { }
	// RVA: 0x2d85fd4 VA: 0x759539dfd4
	private Boolean <>xLuaBaseProxy_CheckAvailInfo(CharViewModel P0) { }
	// RVA: 0x2d85fd8 VA: 0x759539dfd8
	private Void <>xLuaBaseProxy_Render(CharViewModel P0) { }
}
```