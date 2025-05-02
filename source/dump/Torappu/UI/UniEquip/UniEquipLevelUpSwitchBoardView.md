# UniEquipLevelUpSwitchBoardView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Text _simpleText`

- `AnimationWrapper _animationWrapper`

- `SimpleLayoutContent _boardContent`

- `RectTransform _boardContentTransform`

- `HorizontalLayoutGroup _layoutGroup`

- `RectTransform _boardObjTransform`

- `Single _selectTweenDuration`

- `Single _boardInitPosX`

- `BoardAdapter m_boardAdapter`

- `UniEquipLevelUpSwitchBoardViewModel m_cachedModel`

- `Boolean m_isInited`

- `Int32 m_cachedTargetLevel`

- `Tween m_selectTween`


## Methods

- `Void Render(UniEquipLevelUpSwitchBoardViewModel)`

- `Void PlaySwitchAnim(Action)`

- `Void _InitIfNot()`

- `Void _ShowSelectTween()`

- `Void _SetBoardPos()`

- `Void _RenderLevelUpContent(UniEquipLevelUpSwitchBoardViewModel)`

- `Single _CalcPreferredHeightInText(Text, String)`

- `Void _PlayOutAnim(TweenCallback)`

- `Void _PlayInAnim()`

- `Vector2 <_ShowSelectTween>b__19_0()`

- `Void <_ShowSelectTween>b__19_1(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipLevelUpSwitchBoardView : MonoBehaviour, IHotfixable
{
	private const String ANIM_BOARD_OUT; // 0x0
	private const String ANIM_BOARD_IN; // 0x0
	private Text _simpleText; // 0x18
	private AnimationWrapper _animationWrapper; // 0x20
	private SimpleLayoutContent _boardContent; // 0x28
	private RectTransform _boardContentTransform; // 0x30
	private HorizontalLayoutGroup _layoutGroup; // 0x38
	private RectTransform _boardObjTransform; // 0x40
	private Single _selectTweenDuration; // 0x48
	private Single _boardInitPosX; // 0x4c
	private BoardAdapter m_boardAdapter; // 0x50
	private UniEquipLevelUpSwitchBoardViewModel m_cachedModel; // 0x58
	private Boolean m_isInited; // 0x60
	private Int32 m_cachedTargetLevel; // 0x64
	private Tween m_selectTween; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_PlaySwitchAnim; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__ShowSelectTween; // 0x18
	private static DelegateBridge __Hotfix0__SetBoardPos; // 0x20
	private static DelegateBridge __Hotfix0__RenderLevelUpContent; // 0x28
	private static DelegateBridge __Hotfix0__CalcPreferredHeightInText; // 0x30
	private static DelegateBridge __Hotfix0__PlayOutAnim; // 0x38
	private static DelegateBridge __Hotfix0__PlayInAnim; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x23005d8 VA: 0x75949185d8
	public Void Render(UniEquipLevelUpSwitchBoardViewModel viewModel) { }
	// RVA: 0x2300cdc VA: 0x7594918cdc
	public Void PlaySwitchAnim(Action reloadFunc) { }
	// RVA: 0x23006cc VA: 0x75949186cc
	private Void _InitIfNot() { }
	// RVA: 0x23009c4 VA: 0x75949189c4
	private Void _ShowSelectTween() { }
	// RVA: 0x2300c08 VA: 0x7594918c08
	private Void _SetBoardPos() { }
	// RVA: 0x23007b4 VA: 0x75949187b4
	private Void _RenderLevelUpContent(UniEquipLevelUpSwitchBoardViewModel viewModel) { }
	// RVA: 0x2300ec0 VA: 0x7594918ec0
	private Single _CalcPreferredHeightInText(Text text, String content) { }
	// RVA: 0x2300df4 VA: 0x7594918df4
	private Void _PlayOutAnim(TweenCallback onComplete) { }
	// RVA: 0x23011d8 VA: 0x75949191d8
	private Void _PlayInAnim() { }
	// RVA: 0x2301290 VA: 0x7594919290
	public Void .ctor() { }
	// RVA: 0x230130c VA: 0x759491930c
	private Vector2 <_ShowSelectTween>b__19_0() { }
	// RVA: 0x2301328 VA: 0x7594919328
	private Void <_ShowSelectTween>b__19_1(Vector2 val) { }
}
```