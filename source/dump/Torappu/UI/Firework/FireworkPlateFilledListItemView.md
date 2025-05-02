# FireworkPlateFilledListItemView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `CanvasGroup _canvasEmpty`

- `CanvasGroup _canvasNormal`

- `UIAtlasImage _imgEmptyFrame`

- `UIAtlasImage _imgBkg`

- `Image _imgRange`

- `UIAtlasImage _imgFillFrame`

- `CanvasGroup _canvasSelected`

- `UIAtlasImage _imgSelectedFrame`

- `UIAtlasObject _atlasObject`

- `String _spriteFilled`

- `FireworkPlatePieceView _pieceView`

- `UIAtlasImage _imgRangeCenter`

- `UISwitchTween m_filledTween`

- `UISwitchTween m_selectedTween`

- `FilledStatus m_cachedFilledStatus`

- `Boolean m_inited`

- `PlateSlotData m_cachedSlotData`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void Render(PlateSlotData, FireworkPlateGroupModel, FireworkPlateGroupViewStyle)`

- `Void _RenderSelection(Boolean, Boolean)`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateFilledListItemView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasEmpty; // 0x18
	private CanvasGroup _canvasNormal; // 0x20
	private UIAtlasImage _imgEmptyFrame; // 0x28
	private UIAtlasImage _imgBkg; // 0x30
	private Image _imgRange; // 0x38
	private UIAtlasImage _imgFillFrame; // 0x40
	private CanvasGroup _canvasSelected; // 0x48
	private UIAtlasImage _imgSelectedFrame; // 0x50
	private UIAtlasObject _atlasObject; // 0x58
	private String _spriteFilled; // 0x60
	private FireworkPlatePieceView _pieceView; // 0x68
	private UIAtlasImage _imgRangeCenter; // 0x70
	private UISwitchTween m_filledTween; // 0x78
	private UISwitchTween m_selectedTween; // 0x80
	private FilledStatus m_cachedFilledStatus; // 0x88
	private Boolean m_inited; // 0x8c
	private PlateSlotData m_cachedSlotData; // 0x90
	private UIStateFinder m_stateFinder; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderSelection; // 0x10
	private static DelegateBridge __Hotfix0_OnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28ebebc VA: 0x7594f03ebc
	private Void _InitIfNot() { }
	// RVA: 0x28ec088 VA: 0x7594f04088
	public Void Render(PlateSlotData plateSlotData, FireworkPlateGroupModel groupModel, FireworkPlateGroupViewStyle style) { }
	// RVA: 0x28ec59c VA: 0x7594f0459c
	private Void _RenderSelection(Boolean isSelected, Boolean fastMode) { }
	// RVA: 0x28ec644 VA: 0x7594f04644
	public Void OnClicked() { }
	// RVA: 0x28ec728 VA: 0x7594f04728
	public Void .ctor() { }
}
```