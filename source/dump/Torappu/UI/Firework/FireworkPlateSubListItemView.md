# FireworkPlateSubListItemView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `UIAtlasImage _imgBkg`

- `UIAtlasObject _atlasObject`

- `String _spriteFilled`

- `String _spriteNormal`

- `Image _imgRange`

- `UIAtlasImage _imgSelectedFrame`

- `GameObject _pnlFilled`

- `GameObject _pnlFilledCheck`

- `UIAnimationLocation _animShow`

- `Single _delay`

- `FireworkPlatePieceView _pieceView`

- `GameObject _hintGo`

- `UIAtlasImage _imgRangeCenter`

- `Button _hotspotGo`

- `Tween m_showTween`

- `PlateSlotData m_cachedSlotData`

- `UIStateFinder m_stateFinder`

- `Boolean m_cachedPieceHinted`


## Methods

- `Void _PlayAnimShow(Int32)`

- `Void Render(PlateSlotData, FireworkPlateGroupModel, FireworkPlateGroupViewStyle, Boolean)`

- `Void RegisterTutorialGo()`

- `Void OnClicked()`

- `Boolean CanPlayAudio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateSubListItemView : MonoBehaviour, IAudioAnimationPlayerConditionProvider, IHotfixable
{
	private UIAtlasImage _imgBkg; // 0x18
	private UIAtlasObject _atlasObject; // 0x20
	private String _spriteFilled; // 0x28
	private String _spriteNormal; // 0x30
	private Image _imgRange; // 0x38
	private UIAtlasImage _imgSelectedFrame; // 0x40
	private GameObject _pnlFilled; // 0x48
	private GameObject _pnlFilledCheck; // 0x50
	private UIAnimationLocation _animShow; // 0x58
	private Single _delay; // 0x68
	private FireworkPlatePieceView _pieceView; // 0x70
	private GameObject _hintGo; // 0x78
	private UIAtlasImage _imgRangeCenter; // 0x80
	private Button _hotspotGo; // 0x88
	private Tween m_showTween; // 0x90
	private PlateSlotData m_cachedSlotData; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private Boolean m_cachedPieceHinted; // 0xb0
	private static DelegateBridge __Hotfix0__PlayAnimShow; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x10
	private static DelegateBridge __Hotfix0_OnClicked; // 0x18
	private static DelegateBridge __Hotfix0_CanPlayAudio; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x28f1ef4 VA: 0x7594f09ef4
	private Void _PlayAnimShow(Int32 idx) { }
	// RVA: 0x28f2048 VA: 0x7594f0a048
	public Void Render(PlateSlotData plateSlotData, FireworkPlateGroupModel groupModel, FireworkPlateGroupViewStyle style, Boolean isNewGroup) { }
	// RVA: 0x28f2280 VA: 0x7594f0a280
	public Void RegisterTutorialGo() { }
	// RVA: 0x28f2368 VA: 0x7594f0a368
	public Void OnClicked() { }
	// RVA: 0x28f244c VA: 0x7594f0a44c
	public Boolean CanPlayAudio() { }
	// RVA: 0x28f24b4 VA: 0x7594f0a4b4
	public Void .ctor() { }
}
```