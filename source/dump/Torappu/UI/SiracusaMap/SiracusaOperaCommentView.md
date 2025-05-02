# SiracusaOperaCommentView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Text _operaName`

- `Text _operaSubName`

- `Text _score`

- `Text _canLike`

- `Text _totalLike`

- `Text _timeNum`

- `Text _timeUnit`

- `Text _bottomText`

- `GameObject _panelTime`

- `GameObject _panelLike`

- `Image _titleBkg`

- `ScrollRect _scroll`

- `SimpleLayoutContent _content`

- `UIStringEvent _onCommentClicked`

- `Boolean m_isInited`

- `Adapter m_adapter`


## Methods

- `Void OnLikeCancel()`

- `Void _OnCommentClicked(String)`

- `Sprite _LoadTitleBkg(String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaCommentView : DataBinder`1
{
	private Text _operaName; // 0x20
	private Text _operaSubName; // 0x28
	private Text _score; // 0x30
	private Text _canLike; // 0x38
	private Text _totalLike; // 0x40
	private Text _timeNum; // 0x48
	private Text _timeUnit; // 0x50
	private Text _bottomText; // 0x58
	private GameObject _panelTime; // 0x60
	private GameObject _panelLike; // 0x68
	private Image _titleBkg; // 0x70
	private ScrollRect _scroll; // 0x78
	private SimpleLayoutContent _content; // 0x80
	private UIStringEvent _onCommentClicked; // 0x88
	private Boolean m_isInited; // 0x90
	private Adapter m_adapter; // 0x98
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnLikeCancel; // 0x8
	private static DelegateBridge __Hotfix0__OnCommentClicked; // 0x10
	private static DelegateBridge __Hotfix0__LoadTitleBkg; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23f8144 VA: 0x7594a10144
	public override Void OnValueChanged(SiracusaOperaCommentProperty property) { }
	// RVA: 0x23f8a44 VA: 0x7594a10a44
	public Void OnLikeCancel() { }
	// RVA: 0x23f8ad8 VA: 0x7594a10ad8
	private Void _OnCommentClicked(String commentId) { }
	// RVA: 0x23f87c8 VA: 0x7594a107c8
	private Sprite _LoadTitleBkg(String operaId) { }
	// RVA: 0x23f84dc VA: 0x7594a104dc
	private Void _InitIfNot() { }
	// RVA: 0x23f8bf4 VA: 0x7594a10bf4
	public Void .ctor() { }
}
```