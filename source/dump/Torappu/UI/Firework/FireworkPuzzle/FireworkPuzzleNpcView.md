# FireworkPuzzleNpcView

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `UISpineWrapper _spineWrapper`

- `Text _textDesc`

- `Single _textTweenDuration`

- `UIAnimationLocation _animDialogShow`

- `UIAnimationLocation _animDialogHide`

- `Int32 m_cacheEnterSeqNum`

- `Int32 m_cacheAddSeqNum`

- `Int32 m_cacheRemoveSeqNum`

- `Int32 m_cacheHintSuccSeqNum`

- `Int32 m_cacheHintFailSeqNum`

- `Boolean m_hasInited`

- `Tween m_textTween`

- `FireworkNpcDialogModel m_cacheDialogModel`

- `Tween m_dialogTween`

- `Boolean m_cacheDialogVisible`


## Methods

- `Void Render(FireworkPuzzleDetailModel)`

- `Void _PlayDialogTweenIfNeed(Boolean)`

- `Void _InitIfNot()`

- `Void _PlayTextTween(String)`

- `Boolean _TryGetNextDialogType(FireworkPuzzleDetailModel, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleNpcView : MonoBehaviour, IHotfixable
{
	private UISpineWrapper _spineWrapper; // 0x18
	private Text _textDesc; // 0x20
	private Single _textTweenDuration; // 0x28
	private UIAnimationLocation _animDialogShow; // 0x30
	private UIAnimationLocation _animDialogHide; // 0x40
	private Int32 m_cacheEnterSeqNum; // 0x50
	private Int32 m_cacheAddSeqNum; // 0x54
	private Int32 m_cacheRemoveSeqNum; // 0x58
	private Int32 m_cacheHintSuccSeqNum; // 0x5c
	private Int32 m_cacheHintFailSeqNum; // 0x60
	private Boolean m_hasInited; // 0x64
	private Tween m_textTween; // 0x68
	private FireworkNpcDialogModel m_cacheDialogModel; // 0x70
	private Tween m_dialogTween; // 0x78
	private Boolean m_cacheDialogVisible; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayDialogTweenIfNeed; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlayTextTween; // 0x18
	private static DelegateBridge __Hotfix0__TryGetNextDialogType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x28fd058 VA: 0x7594f15058
	public Void Render(FireworkPuzzleDetailModel detailModel) { }
	// RVA: 0x28fda00 VA: 0x7594f15a00
	private Void _PlayDialogTweenIfNeed(Boolean isShow) { }
	// RVA: 0x28fd7b8 VA: 0x7594f157b8
	private Void _InitIfNot() { }
	// RVA: 0x28fdb4c VA: 0x7594f15b4c
	private Void _PlayTextTween(String rawDesc) { }
	// RVA: 0x28fd858 VA: 0x7594f15858
	private Boolean _TryGetNextDialogType(FireworkPuzzleDetailModel detailModel, out NpcDialogType dialogType) { }
	// RVA: 0x28fdcac VA: 0x7594f15cac
	public Void .ctor() { }
}
```