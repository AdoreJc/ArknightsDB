# MissionRewardPreviewItem

**Namespace:** `Torappu.UI.Mission`


## Fields

- `Transform _itemCardContainer`

- `Single _cardScaleFactor`

- `Boolean _showItemNum`

- `GameObject _countPanel`

- `Text _countLabel`

- `Boolean _useOriginCountLabel`

- `Boolean _usePreviewCountLabel`

- `Boolean _useOriginCountBackground`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_viewModel`

- `Boolean m_isInited`


## Methods

- `Void Render(UIItemViewModel)`

- `Void <_InitIfNeeded>b__12_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionRewardPreviewItem : MonoBehaviour, IHotfixable
{
	protected Transform _itemCardContainer; // 0x18
	protected Single _cardScaleFactor; // 0x20
	protected Boolean _showItemNum; // 0x24
	private GameObject _countPanel; // 0x28
	private Text _countLabel; // 0x30
	private Boolean _useOriginCountLabel; // 0x38
	private Boolean _usePreviewCountLabel; // 0x39
	private Boolean _useOriginCountBackground; // 0x3a
	protected UIItemCard m_itemCard; // 0x40
	protected UIItemViewModel m_viewModel; // 0x48
	protected Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNeeded; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x274389c VA: 0x7594d5b89c
	public Void Render(UIItemViewModel viewModel) { }
	// RVA: 0x2743a7c VA: 0x7594d5ba7c
	protected virtual Void _InitIfNeeded() { }
	// RVA: 0x2743c94 VA: 0x7594d5bc94
	public Void .ctor() { }
	// RVA: 0x2743d0c VA: 0x7594d5bd0c
	private Void <_InitIfNeeded>b__12_0(Int32 _) { }
}
```