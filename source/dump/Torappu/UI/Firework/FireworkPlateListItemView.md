# FireworkPlateListItemView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `GameObject _pnlTag`

- `UIAtlasImage _imgTagBkg`

- `Text _imgTagText`

- `UIAtlasImage _imgBkg`

- `Image _imgRange`

- `CanvasGroup _previewingAlphaHandler`

- `UIAtlasImage _imgSelectedLight`

- `GameObject _panelNew`

- `UIAtlasObject _atlasObject`

- `String _spriteFilled`

- `String _spriteNormal`

- `FireworkPlatePieceView _pieceView`

- `GameObject _hintGo`

- `UIAnimationLocation _animHint`

- `UIAtlasImage _imgRangeCenter`

- `Button _hotspotGo`

- `Boolean m_inited`

- `UISwitchTween m_previewingTween`

- `String m_cachedGroupId`

- `UIStateFinder m_stateFinder`

- `Tween m_hintTween`

- `Int32 m_cacheHintSeqNum`

- `Int32 m_cacheHintCount`


## Methods

- `Void _InitIfNot()`

- `Void Render(FireworkPieceGroupModel, FireworkPlateGroupModel, FireworkPlateGroupViewStyle)`

- `Void _UpdateHintDisplay(FireworkPlateGroupModel, FireworkPieceGroupModel)`

- `Void RegisterTutorialGo()`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateListItemView : MonoBehaviour, IHotfixable
{
	private GameObject _pnlTag; // 0x18
	private UIAtlasImage _imgTagBkg; // 0x20
	private Text _imgTagText; // 0x28
	private UIAtlasImage _imgBkg; // 0x30
	private Image _imgRange; // 0x38
	private CanvasGroup _previewingAlphaHandler; // 0x40
	private UIAtlasImage _imgSelectedLight; // 0x48
	private GameObject _panelNew; // 0x50
	private UIAtlasObject _atlasObject; // 0x58
	private String _spriteFilled; // 0x60
	private String _spriteNormal; // 0x68
	private FireworkPlatePieceView _pieceView; // 0x70
	private GameObject _hintGo; // 0x78
	private UIAnimationLocation _animHint; // 0x80
	private UIAtlasImage _imgRangeCenter; // 0x90
	private Button _hotspotGo; // 0x98
	private Boolean m_inited; // 0xa0
	private UISwitchTween m_previewingTween; // 0xa8
	private String m_cachedGroupId; // 0xb0
	private UIStateFinder m_stateFinder; // 0xb8
	private Tween m_hintTween; // 0xc8
	private Int32 m_cacheHintSeqNum; // 0xd0
	private Int32 m_cacheHintCount; // 0xd4
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__UpdateHintDisplay; // 0x10
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x18
	private static DelegateBridge __Hotfix0_OnClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x28efa44 VA: 0x7594f07a44
	private Void _InitIfNot() { }
	// RVA: 0x28efb28 VA: 0x7594f07b28
	public Void Render(FireworkPieceGroupModel pieceGroupModel, FireworkPlateGroupModel groupModel, FireworkPlateGroupViewStyle style) { }
	// RVA: 0x28efe40 VA: 0x7594f07e40
	private Void _UpdateHintDisplay(FireworkPlateGroupModel groupModel, FireworkPieceGroupModel pieceGroupModel) { }
	// RVA: 0x28f0024 VA: 0x7594f08024
	public Void RegisterTutorialGo() { }
	// RVA: 0x28f010c VA: 0x7594f0810c
	public Void OnClicked() { }
	// RVA: 0x28f0224 VA: 0x7594f08224
	public Void .ctor() { }
}
```