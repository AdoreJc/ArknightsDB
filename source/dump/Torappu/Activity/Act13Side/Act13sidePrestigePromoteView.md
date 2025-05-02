# Act13sidePrestigePromoteView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `RectTransform _animEmojiContainer`

- `Image _imgLogo`

- `Image _imgTitle`

- `Image _imgEmojiLast`

- `Text _textRankLast`

- `Text _textRankCurrent`

- `SimpleLayoutContent _rewardList`

- `UIAnimationLocation _enterAnim`

- `RectTransform _backRt`

- `Single _enterAnimDelay`

- `Single _emojiAnimDelay`

- `Single _interactDelay`

- `Action onReturn`

- `Boolean m_hasInited`

- `Boolean m_canInteract`

- `OrgData m_orgData`

- `Adapter m_adapter`

- `Act13sideAnimEmojiView m_animEmoji`


## Methods

- `Void Render(String, String, PrestigeRank, PrestigeRank)`

- `IEnumerator _EnableInteract()`

- `Void _InitIfNot()`

- `Void CloseSelf()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sidePrestigePromoteView : MonoBehaviour, IHotfixable
{
	private AnimEmojiStruct[] _animStructList; // 0x18
	private RectTransform _animEmojiContainer; // 0x20
	private Image _imgLogo; // 0x28
	private Image _imgTitle; // 0x30
	private Image _imgEmojiLast; // 0x38
	private Text _textRankLast; // 0x40
	private Text _textRankCurrent; // 0x48
	private SimpleLayoutContent _rewardList; // 0x50
	private UIAnimationLocation _enterAnim; // 0x58
	private RectTransform _backRt; // 0x68
	private Single _enterAnimDelay; // 0x70
	private Single _emojiAnimDelay; // 0x74
	private Single _interactDelay; // 0x78
	public Action onReturn; // 0x80
	private Boolean m_hasInited; // 0x88
	private Boolean m_canInteract; // 0x89
	private OrgData m_orgData; // 0x90
	private Adapter m_adapter; // 0x98
	private Act13sideAnimEmojiView m_animEmoji; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__EnableInteract; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_CloseSelf; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3433f5c VA: 0x7595a4bf5c
	public Void Render(String actId, String orgId, PrestigeRank lastRank, PrestigeRank currentRank) { }
	// RVA: 0x3443ac8 VA: 0x7595a5bac8
	private IEnumerator _EnableInteract() { }
	// RVA: 0x344353c VA: 0x7595a5b53c
	private Void _InitIfNot() { }
	// RVA: 0x3443c60 VA: 0x7595a5bc60
	public Void CloseSelf() { }
	// RVA: 0x3443d0c VA: 0x7595a5bd0c
	public Void .ctor() { }
}
```