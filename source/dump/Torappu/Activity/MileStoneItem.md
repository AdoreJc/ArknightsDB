# MileStoneItem

**Namespace:** `Torappu.Activity`


## Fields

- `UIStringEvent clickEvent`

- `Single _scaleInfo`

- `Transform _itemViewContainer`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `String m_cacheId`


## Properties

- `UIItemCard itemCard`


## Methods

- `UIItemCard get_itemCard()`

- `Void _Inited()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class MileStoneItem : MonoBehaviour, IHotfixable
{
	public UIStringEvent clickEvent; // 0x18
	private Single _scaleInfo; // 0x20
	private Transform _itemViewContainer; // 0x28
	private Boolean m_isInited; // 0x30
	private UIItemCard m_itemCard; // 0x38
	private String m_cacheId; // 0x40
	private static DelegateBridge __Hotfix0_get_itemCard; // 0x0
	private static DelegateBridge __Hotfix0__Inited; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_InitData; // 0x18
	private static DelegateBridge __Hotfix0_OnRenderDataPart; // 0x20
	private static DelegateBridge __Hotfix0_OnRenderItemStyle; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected UIItemCard itemCard { get; }

	// RVA: 0x30c6750 VA: 0x75956de750
	protected UIItemCard get_itemCard() { }
	// RVA: 0x30c67b8 VA: 0x75956de7b8
	private Void _Inited() { }
	// RVA: 0x30c6958 VA: 0x75956de958
	public Void OnClick() { }
	// RVA: 0x30c69ec VA: 0x75956de9ec
	public virtual Void InitData(MileStoneViewModel viewModel) { }
	// RVA: 0x30c6aa8 VA: 0x75956deaa8
	protected virtual Void OnRenderDataPart(MileStoneViewModel viewModel) { }
	// RVA: 0x30c6b98 VA: 0x75956deb98
	protected virtual Void OnRenderItemStyle(PartType part, State state) { }
	// RVA: 0x30c6c18 VA: 0x75956dec18
	public Void .ctor() { }
}
```