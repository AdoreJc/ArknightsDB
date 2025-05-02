# RoguelikeTopicMonthSquadCharPortraitView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Image _rarityImg`

- `Image _professionImg`

- `Text _charName`

- `UIAtlasImage _charPortrait`

- `GameObject _panelBtn`

- `RectTransform _anchor`

- `CanvasGroup _anchorCanvasGroup`

- `RoguelikeTopicMonthSquadTeamChar m_cachedTeamCharModel`

- `String m_cachedCharId`

- `TweenWrapper m_tween`


## Methods

- `Void Render(RoguelikeTopicMonthSquadTeamChar, Boolean, Boolean)`

- `Void TweenToChar(Boolean, RoguelikeTopicMonthSquadTeamChar, Boolean)`

- `Void OnBtnCharProtraitClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthSquadCharPortraitView : MonoBehaviour, IHotfixable
{
	private const Single CHAR_CARD_WIDTH; // 0x0
	private Image _rarityImg; // 0x18
	private Image _professionImg; // 0x20
	private Text _charName; // 0x28
	private UIAtlasImage _charPortrait; // 0x30
	private GameObject _panelBtn; // 0x38
	private RectTransform _anchor; // 0x40
	private CanvasGroup _anchorCanvasGroup; // 0x48
	private RoguelikeTopicMonthSquadTeamChar m_cachedTeamCharModel; // 0x50
	private String m_cachedCharId; // 0x58
	private TweenWrapper m_tween; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_TweenToChar; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnCharProtraitClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x26532f4 VA: 0x7594c6b2f4
	public Void Render(RoguelikeTopicMonthSquadTeamChar teamCharModel, Boolean showBtn, Boolean showCharName) { }
	// RVA: 0x2653618 VA: 0x7594c6b618
	public Void TweenToChar(Boolean toPrev, RoguelikeTopicMonthSquadTeamChar teamChar, Boolean showBtn) { }
	// RVA: 0x26556a0 VA: 0x7594c6d6a0
	public Void OnBtnCharProtraitClicked() { }
	// RVA: 0x26557b0 VA: 0x7594c6d7b0
	public Void .ctor() { }
}
```