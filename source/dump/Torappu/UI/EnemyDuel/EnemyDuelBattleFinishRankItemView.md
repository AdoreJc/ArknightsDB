# EnemyDuelBattleFinishRankItemView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `TwoStateToggle _emptyToggle`

- `Text _rank`

- `Color _playerRankColor`

- `Color _defaultRankColor`

- `Text _name`

- `Text _nickId`

- `Text _num`

- `TwoStateToggle _iconToggle`

- `TwoStateToggle _avatarToggle`

- `Transform _avatarContainer`

- `Image _npcAvatar`

- `Single _avatarScale`

- `GameObject _playerFrame`

- `UIAnimationLocation _arrowAnim`

- `Image _imageBG`


## Methods

- `Void Render(SettlementRankItemModel, Int32)`

- `Void _RenderAvatar(SettlementRankItemModel)`

- `Void _RenderNameCardSkin(String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattleFinishRankItemView : UIStylerApplier`1, IHotfixable
{
	private const String NICK_ID_FORMAT; // 0x0
	private const String DEFAULT_SKIN_ID; // 0x0
	private TwoStateToggle _emptyToggle; // 0x20
	private Text _rank; // 0x28
	private Color _playerRankColor; // 0x30
	private Color _defaultRankColor; // 0x40
	private Text _name; // 0x50
	private Text _nickId; // 0x58
	private Text _num; // 0x60
	private TwoStateToggle _iconToggle; // 0x68
	private TwoStateToggle _avatarToggle; // 0x70
	private Transform _avatarContainer; // 0x78
	private Image _npcAvatar; // 0x80
	private Single _avatarScale; // 0x88
	private GameObject _playerFrame; // 0x90
	private UIAnimationLocation _arrowAnim; // 0x98
	private Image _imageBG; // 0xa8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x8
	private static DelegateBridge __Hotfix0__RenderAvatar; // 0x10
	private static DelegateBridge __Hotfix0__RenderNameCardSkin; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x293d838 VA: 0x7594f55838
	public Void Render(SettlementRankItemModel model, Int32 index) { }
	// RVA: 0x293de7c VA: 0x7594f55e7c
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x293db94 VA: 0x7594f55b94
	private Void _RenderAvatar(SettlementRankItemModel model) { }
	// RVA: 0x293dd50 VA: 0x7594f55d50
	private Void _RenderNameCardSkin(String skinId, Int32 tmpl) { }
	// RVA: 0x293dfc8 VA: 0x7594f55fc8
	public Void .ctor() { }
}
```