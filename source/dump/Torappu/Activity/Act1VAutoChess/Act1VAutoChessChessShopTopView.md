# Act1VAutoChessChessShopTopView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `CanvasGroup _canvasListInfoPart`

- `GameObject _objAssistMask`

- `GameObject _objAssist`

- `Button _btnAssist`

- `Text _txtAssistInfo`

- `CanvasGroup _canvasQuickSetPart`

- `GameObject _objAssistNumFull`

- `UIAnimationLocation _editTypeSwitchAnim`

- `Boolean m_hasInited`

- `Boolean m_cachedCanAsssit`

- `UIStateFinder m_stateFinder`

- `FadeSwitchTween m_tweenListInfoPart`

- `FadeSwitchTween m_tweenQuickSetPart`

- `AnimationSwitchTween m_editTypeSwitchTween`

- `Act1VAutoChessShopQuickEditType m_cachedQuickEditType`


## Methods

- `Void Render(Act1VAutoChessShopStatus, Int32, Int32, Boolean, Int32, Act1VAutoChessShopQuickEditType)`

- `Void TutorialOnly_RegisterTutorialGo()`

- `Void _InitIfNot()`

- `Void OnClickAssistCantMask()`

- `Void OnClickAssistBtn()`

- `Void OnClickQuickSetBtn()`

- `Void OnClickEditTypeToggle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopTopView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasListInfoPart; // 0x18
	private GameObject _objAssistMask; // 0x20
	private GameObject _objAssist; // 0x28
	private Button _btnAssist; // 0x30
	private Text _txtAssistInfo; // 0x38
	private CanvasGroup _canvasQuickSetPart; // 0x40
	private GameObject _objAssistNumFull; // 0x48
	private UIAnimationLocation _editTypeSwitchAnim; // 0x50
	private Boolean m_hasInited; // 0x60
	private Boolean m_cachedCanAsssit; // 0x61
	private UIStateFinder m_stateFinder; // 0x68
	private FadeSwitchTween m_tweenListInfoPart; // 0x78
	private FadeSwitchTween m_tweenQuickSetPart; // 0x80
	private AnimationSwitchTween m_editTypeSwitchTween; // 0x88
	private Act1VAutoChessShopQuickEditType m_cachedQuickEditType; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterTutorialGo; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnClickAssistCantMask; // 0x18
	private static DelegateBridge __Hotfix0_OnClickAssistBtn; // 0x20
	private static DelegateBridge __Hotfix0_OnClickQuickSetBtn; // 0x28
	private static DelegateBridge __Hotfix0_OnClickEditTypeToggle; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x33148d8 VA: 0x759592c8d8
	public Void Render(Act1VAutoChessShopStatus shopStatus, Int32 curAssistCnt, Int32 maxCanAssistCnt, Boolean hasNotTopicChar, Int32 notTopicCharCnt, Act1VAutoChessShopQuickEditType quickEditType) { }
	// RVA: 0x3315658 VA: 0x759592d658
	public Void TutorialOnly_RegisterTutorialGo() { }
	// RVA: 0x3316ba0 VA: 0x759592eba0
	private Void _InitIfNot() { }
	// RVA: 0x3316d5c VA: 0x759592ed5c
	public Void OnClickAssistCantMask() { }
	// RVA: 0x3316e0c VA: 0x759592ee0c
	public Void OnClickAssistBtn() { }
	// RVA: 0x3316ec8 VA: 0x759592eec8
	public Void OnClickQuickSetBtn() { }
	// RVA: 0x3316f7c VA: 0x759592ef7c
	public Void OnClickEditTypeToggle() { }
	// RVA: 0x3317090 VA: 0x759592f090
	public Void .ctor() { }
}
```