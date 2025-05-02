# AVGImagePanel

**Namespace:** `Torappu.AVG`


## Fields

- `Image _foreImage`

- `Image _backImage`

- `Ease _fadeEase`

- `Vector2 _screenAdaptReferenceResolution`

- `RectTransform _rectTransform`

- `PostDisplayHandler m_forePostDisplay`

- `PostDisplayHandler m_backPostDisplay`


## Methods

- `Void _BindCamEffectTarget()`

- `Void _BindPostDisplay(ref, String, Image, AVGSceneEffectManager)`

- `Boolean _ExecuteImageRotate(Command)`

- `Boolean _ExecuteImage(Command)`

- `Boolean _ExecuteImageTween(Command)`

- `Boolean _LoadImage(Image, Command)`

- `Single CalculateFadetime(Single)`

- `Boolean NeedSkipAnimation(Single)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnStoryBegin(Story)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGImagePanel : ExecutorComponent, IContainsResRefs, IFadeTimeRatio
{
	private static readonly Dictionary`2 SCREEN_ADAPT_FUNCTION_MAP; // 0x0
	protected Image _foreImage; // 0x50
	protected Image _backImage; // 0x58
	protected Ease _fadeEase; // 0x60
	protected Vector2 _screenAdaptReferenceResolution; // 0x64
	protected RectTransform _rectTransform; // 0x70
	private PostDisplayHandler m_forePostDisplay; // 0x78
	private PostDisplayHandler m_backPostDisplay; // 0x80
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0_OnReset; // 0x10
	private static DelegateBridge __Hotfix0_OnStoryBegin; // 0x18
	private static DelegateBridge __Hotfix0_PostDisplayKey1; // 0x20
	private static DelegateBridge __Hotfix0_PostDisplayKey2; // 0x28
	private static DelegateBridge __Hotfix0_GetPostDisplayType; // 0x30
	private static DelegateBridge __Hotfix0__BindCamEffectTarget; // 0x38
	private static DelegateBridge __Hotfix0__BindPostDisplay; // 0x40
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0x48
	private static DelegateBridge __Hotfix0__ExecuteImageRotate; // 0x50
	private static DelegateBridge __Hotfix0__ExecuteImage; // 0x58
	private static DelegateBridge __Hotfix0__ExecuteImageTween; // 0x60
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x68
	private static DelegateBridge __Hotfix0__LoadImage; // 0x70
	private static DelegateBridge __Hotfix0__LoadSprite; // 0x78
	private static DelegateBridge __Hotfix0__SwapImages; // 0x80
	private static DelegateBridge __Hotfix0__ResetImage; // 0x88
	private static DelegateBridge __Hotfix0__AdaptScreenWidth; // 0x90
	private static DelegateBridge __Hotfix0__AdaptScreenHeight; // 0x98
	private static DelegateBridge __Hotfix0__AdaptScreenShowAll; // 0xa0
	private static DelegateBridge __Hotfix0__AdaptScreenCoverAll; // 0xa8
	private static DelegateBridge __Hotfix0__AdaptScreenFill; // 0xb0
	private static DelegateBridge __Hotfix0_CalculateFadetime; // 0xb8
	private static DelegateBridge __Hotfix0_NeedSkipAnimation; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8


	// RVA: 0x3e6fe44 VA: 0x7596487e44
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e70054 VA: 0x7596488054
	public override Void OnReset() { }
	// RVA: 0x3e70284 VA: 0x7596488284
	public override Void OnStoryBegin(Story story) { }
	// RVA: 0x3e70410 VA: 0x7596488410
	protected virtual String PostDisplayKey1() { }
	// RVA: 0x3e7049c VA: 0x759648849c
	protected virtual String PostDisplayKey2() { }
	// RVA: 0x3e70528 VA: 0x7596488528
	protected virtual PostDisplayType GetPostDisplayType() { }
	// RVA: 0x3e70310 VA: 0x7596488310
	private Void _BindCamEffectTarget() { }
	// RVA: 0x3e705a0 VA: 0x75964885a0
	private Void _BindPostDisplay(ref PostDisplayHandler handler, String key, Image image, AVGSceneEffectManager effectMgr) { }
	// RVA: 0x3e70710 VA: 0x7596488710
	public virtual AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e707b4 VA: 0x75964887b4
	private Boolean _ExecuteImageRotate(Command command) { }
	// RVA: 0x3e70b84 VA: 0x7596488b84
	protected Boolean _ExecuteImage(Command command) { }
	// RVA: 0x3e71738 VA: 0x7596489738
	protected Boolean _ExecuteImageTween(Command command) { }
	// RVA: 0x3e71e28 VA: 0x7596489e28
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e71200 VA: 0x7596489200
	private Boolean _LoadImage(Image image, Command command) { }
	// RVA: 0x3e71e9c VA: 0x7596489e9c
	protected virtual Sprite _LoadSprite(String key) { }
	// RVA: 0x3e710dc VA: 0x75964890dc
	private static Void _SwapImages(ref Image lhs, ref Image rhs, ref PostDisplayHandler lHandler, ref PostDisplayHandler rHandler) { }
	// RVA: 0x3e701b4 VA: 0x75964881b4
	private static Void _ResetImage(Image img) { }
	// RVA: 0x3e71fe0 VA: 0x7596489fe0
	private static Vector2 _AdaptScreenWidth(Vector2 target, Vector2 reference) { }
	// RVA: 0x3e72088 VA: 0x759648a088
	private static Vector2 _AdaptScreenHeight(Vector2 target, Vector2 reference) { }
	// RVA: 0x3e72130 VA: 0x759648a130
	private static Vector2 _AdaptScreenShowAll(Vector2 target, Vector2 reference) { }
	// RVA: 0x3e72228 VA: 0x759648a228
	private static Vector2 _AdaptScreenCoverAll(Vector2 target, Vector2 reference) { }
	// RVA: 0x3e72320 VA: 0x759648a320
	private static Vector2 _AdaptScreenFill(Vector2 target, Vector2 reference) { }
	// RVA: 0x3e70acc VA: 0x7596488acc
	public Single CalculateFadetime(Single initialFadetime) { }
	// RVA: 0x3e723c4 VA: 0x759648a3c4
	public Boolean NeedSkipAnimation(Single fadetime) { }
	// RVA: 0x3e72478 VA: 0x759648a478
	public Void .ctor() { }
	// RVA: 0x3e72500 VA: 0x759648a500
	private static Void .cctor() { }
	// RVA: 0x3e72794 VA: 0x759648a794
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e7279c VA: 0x759648a79c
	private Void <>xLuaBaseProxy_OnStoryBegin(Story P0) { }
}
```