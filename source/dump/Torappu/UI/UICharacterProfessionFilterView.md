# UICharacterProfessionFilterView

**Namespace:** `Torappu.UI`


## Fields

- `Text _selectedName`

- `GameObject _panelSelected`

- `GameObject _panelUnSelected`

- `GameObject _panelSubProfBlocker`

- `UICharacterProfessionFilterProfView _profView`

- `UICharacterProfessionFilterSubProfView _subProfView`

- `UIAnimationLocation _profBarAnim`

- `UIAnimationLocation _subProfBarAnim`

- `ILoadAsset assetLoader`

- `Action onBarTopClick`

- `Action onCloseSubClick`

- `Int32 m_fastSeq`

- `Int32 m_profChangeSeq`

- `Boolean m_isInited`

- `AnimationSwitchTween m_profShow`

- `AnimationSwitchTween m_subProfShow`


## Methods

- `Void _InitIfNot()`

- `Void _RenderImpl(UICharacterProfessionFilterViewModel)`

- `Void _SetPanelShow(Boolean, Boolean, Boolean)`

- `Void OnBarTopClick()`

- `Void OnCloseSubProfClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterProfessionFilterView : DataBinder`1
{
	private Text _selectedName; // 0x20
	private GameObject _panelSelected; // 0x28
	private GameObject _panelUnSelected; // 0x30
	private GameObject _panelSubProfBlocker; // 0x38
	private UICharacterProfessionFilterProfView _profView; // 0x40
	private UICharacterProfessionFilterSubProfView _subProfView; // 0x48
	private UIAnimationLocation _profBarAnim; // 0x50
	private UIAnimationLocation _subProfBarAnim; // 0x60
	public ILoadAsset assetLoader; // 0x70
	public Action`2 onProfessionClick; // 0x78
	public Action`2 onSubProfessionClick; // 0x80
	public Action onBarTopClick; // 0x88
	public Action onCloseSubClick; // 0x90
	private Int32 m_fastSeq; // 0x98
	private Int32 m_profChangeSeq; // 0x9c
	private Boolean m_isInited; // 0xa0
	private AnimationSwitchTween m_profShow; // 0xa8
	private AnimationSwitchTween m_subProfShow; // 0xb0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__RenderImpl; // 0x10
	private static DelegateBridge __Hotfix0__SetPanelShow; // 0x18
	private static DelegateBridge __Hotfix0_OnBarTopClick; // 0x20
	private static DelegateBridge __Hotfix0_OnCloseSubProfClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x21270a8 VA: 0x759473f0a8
	private Void _InitIfNot() { }
	// RVA: 0x212725c VA: 0x759473f25c
	public override Void OnValueChanged(UICharacterProfessionFilterProperty property) { }
	// RVA: 0x2127484 VA: 0x759473f484
	private Void _RenderImpl(UICharacterProfessionFilterViewModel model) { }
	// RVA: 0x212738c VA: 0x759473f38c
	private Void _SetPanelShow(Boolean isProfShow, Boolean isSubProfShow, Boolean isFastMode) { }
	// RVA: 0x2127724 VA: 0x759473f724
	public Void OnBarTopClick() { }
	// RVA: 0x21277a8 VA: 0x759473f7a8
	public Void OnCloseSubProfClick() { }
	// RVA: 0x212782c VA: 0x759473f82c
	public Void .ctor() { }
}
```