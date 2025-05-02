# SkinGroupCommonView

**Namespace:** `Torappu.UI.Skin`


## Fields

- `Image _avatarImage`

- `Image _portraitImage`

- `Transform _illustContainer`

- `UICharSpineHolder _spineHolder`

- `Animator _animator`

- `Text _drawerName`

- `Text _pureDrawerName`

- `Text _modelName`

- `Text _pureModelName`

- `Text _content`

- `UIAutoSlideRect _autoSlideRect`

- `Boolean m_isInited`

- `UICharacterIllust m_illust`

- `UIAtlasImage m_portraitImg`

- `Int32 index`

- `String m_cachedSkinId`


## Methods

- `Void _InitIfNot()`

- `Void ApplyState(Single)`

- `Void SetIllustVisible(Boolean)`

- `Void ApplyData(Int32, SkinSelectViewModel, UIPage)`

- `Void _SetDrawerName(String)`

- `Void _SetModelName(String)`

- `Void _TryLoadSpineIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinGroupCommonView : MonoBehaviour, IHotfixable
{
	private List`1 _toColor; // 0x18
	private Image _avatarImage; // 0x20
	private Image _portraitImage; // 0x28
	private Transform _illustContainer; // 0x30
	private UICharSpineHolder _spineHolder; // 0x38
	private Animator _animator; // 0x40
	private Text _drawerName; // 0x48
	private Text _pureDrawerName; // 0x50
	private Text _modelName; // 0x58
	private Text _pureModelName; // 0x60
	private Text _content; // 0x68
	private UIAutoSlideRect _autoSlideRect; // 0x70
	private Boolean m_isInited; // 0x78
	private UICharacterIllust m_illust; // 0x80
	private UIAtlasImage m_portraitImg; // 0x88
	public Int32 index; // 0x90
	private String m_cachedSkinId; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_ApplyState; // 0x8
	private static DelegateBridge __Hotfix0_SetIllustVisible; // 0x10
	private static DelegateBridge __Hotfix0_ApplyData; // 0x18
	private static DelegateBridge __Hotfix0__SetDrawerName; // 0x20
	private static DelegateBridge __Hotfix0__SetModelName; // 0x28
	private static DelegateBridge __Hotfix0__TryLoadSpineIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x23d234c VA: 0x75949ea34c
	private Void _InitIfNot() { }
	// RVA: 0x23d2560 VA: 0x75949ea560
	public Void ApplyState(Single state) { }
	// RVA: 0x23d2810 VA: 0x75949ea810
	public Void SetIllustVisible(Boolean isVisible) { }
	// RVA: 0x23d28a4 VA: 0x75949ea8a4
	public Void ApplyData(Int32 index, SkinSelectViewModel viewModel, UIPage page) { }
	// RVA: 0x23d3004 VA: 0x75949eb004
	private Void _SetDrawerName(String name) { }
	// RVA: 0x23d2ea4 VA: 0x75949eaea4
	private Void _SetModelName(String name) { }
	// RVA: 0x23d2750 VA: 0x75949ea750
	private Void _TryLoadSpineIfNot() { }
	// RVA: 0x23d3164 VA: 0x75949eb164
	public Void .ctor() { }
}
```