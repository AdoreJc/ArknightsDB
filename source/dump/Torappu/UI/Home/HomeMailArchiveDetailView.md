# HomeMailArchiveDetailView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _icon`

- `Text _title`

- `Text _name`

- `Text _time`

- `Text _content`

- `SimpleLayoutContent _itemContent`

- `ScrollRect _scrollRect`

- `UIAnimationLocation _leftAnim`

- `UIAnimationLocation _rightAnim`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `UIStateFinder m_stateFinder`

- `Int32 m_enterSeq`

- `Int32 m_prevSeq`

- `Int32 m_nextSeq`

- `Tween m_cachedTween`

- `HomeMailArchiveDetailViewModel m_cachedViewModel`


## Methods

- `Void _InitIfNot()`

- `Void _PlayAnim(Boolean)`

- `Void _PlayAnimImpl(UIAnimationLocation, UIAnimationLocation)`

- `Void _UpdateView()`

- `Void OnPrevClick()`

- `Void OnNextClick()`

- `Void OnCloseClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveDetailView : DataBinder`1
{
	private Image _icon; // 0x20
	private Text _title; // 0x28
	private Text _name; // 0x30
	private Text _time; // 0x38
	private Text _content; // 0x40
	private SimpleLayoutContent _itemContent; // 0x48
	private ScrollRect _scrollRect; // 0x50
	private UIAnimationLocation _leftAnim; // 0x58
	private UIAnimationLocation _rightAnim; // 0x68
	private GameObject[] _panelSwitchBtn; // 0x78
	private Boolean m_isInited; // 0x80
	private Adapter m_adapter; // 0x88
	private UIStateFinder m_stateFinder; // 0x90
	private Int32 m_enterSeq; // 0xa0
	private Int32 m_prevSeq; // 0xa4
	private Int32 m_nextSeq; // 0xa8
	private Tween m_cachedTween; // 0xb0
	private HomeMailArchiveDetailViewModel m_cachedViewModel; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnimImpl; // 0x18
	private static DelegateBridge __Hotfix0__UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_OnPrevClick; // 0x28
	private static DelegateBridge __Hotfix0_OnNextClick; // 0x30
	private static DelegateBridge __Hotfix0_OnCloseClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x28458a4 VA: 0x7594e5d8a4
	private Void _InitIfNot() { }
	// RVA: 0x2845a08 VA: 0x7594e5da08
	public override Void OnValueChanged(HomeMailArchiveDetailProperty property) { }
	// RVA: 0x2845db4 VA: 0x7594e5ddb4
	private Void _PlayAnim(Boolean isNext) { }
	// RVA: 0x2845e48 VA: 0x7594e5de48
	private Void _PlayAnimImpl(UIAnimationLocation firstAnim, UIAnimationLocation secondAnim) { }
	// RVA: 0x2845b8c VA: 0x7594e5db8c
	private Void _UpdateView() { }
	// RVA: 0x2846068 VA: 0x7594e5e068
	public Void OnPrevClick() { }
	// RVA: 0x284611c VA: 0x7594e5e11c
	public Void OnNextClick() { }
	// RVA: 0x28461d0 VA: 0x7594e5e1d0
	public Void OnCloseClick() { }
	// RVA: 0x2846284 VA: 0x7594e5e284
	public Void .ctor() { }
}
```