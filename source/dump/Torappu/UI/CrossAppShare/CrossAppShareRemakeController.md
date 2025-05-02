# CrossAppShareRemakeController

**Namespace:** `Torappu.UI.CrossAppShare`


## Fields

- `CrossAppShareRemakeModelApplier _remakeModelApplier`

- `CrossAppShareRemakeAdditionBaseView _remakeAdditionView`

- `UIAnimationLocation _showAnim`

- `CanvasGroup _canvasGroup`

- `Vector2 _renderResolution`

- `Vector2 _shotResolution`

- `String _showAnimAudioSignalCanBeEmpty`

- `Tween m_showTween`


## Properties

- `Vector2 renderResolution`

- `Vector2 shotResolution`


## Methods

- `Vector2 get_renderResolution()`

- `Vector2 get_shotResolution()`

- `Void RemakeShareWindow(ICrossAppShareModelCollector, ILoadAsset, ICrossAppShareRemakeAdditionBaseModel)`

- `Void PlayShowAnim()`

- `Void SetRemakeGroupShow(Boolean)`

- `Void _EnsureCanvasGroupBlockRaycastFalse()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrossAppShare
public class CrossAppShareRemakeController : MonoBehaviour, IHotfixable
{
	private CrossAppShareRemakeModelApplier _remakeModelApplier; // 0x18
	private CrossAppShareRemakeAdditionBaseView _remakeAdditionView; // 0x20
	private UIAnimationLocation _showAnim; // 0x28
	private CanvasGroup _canvasGroup; // 0x38
	private Vector2 _renderResolution; // 0x40
	private Vector2 _shotResolution; // 0x48
	private String _showAnimAudioSignalCanBeEmpty; // 0x50
	private Tween m_showTween; // 0x58
	private static DelegateBridge __Hotfix0_get_renderResolution; // 0x0
	private static DelegateBridge __Hotfix0_get_shotResolution; // 0x8
	private static DelegateBridge __Hotfix0_RemakeShareWindow; // 0x10
	private static DelegateBridge __Hotfix0_PlayShowAnim; // 0x18
	private static DelegateBridge __Hotfix0_SetRemakeGroupShow; // 0x20
	private static DelegateBridge __Hotfix0__EnsureCanvasGroupBlockRaycastFalse; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Vector2 renderResolution { get; }
	public Vector2 shotResolution { get; }

	// RVA: 0x2bbed68 VA: 0x75951d6d68
	public Vector2 get_renderResolution() { }
	// RVA: 0x2bbedcc VA: 0x75951d6dcc
	public Vector2 get_shotResolution() { }
	// RVA: 0x2bbe260 VA: 0x75951d6260
	public Void RemakeShareWindow(ICrossAppShareModelCollector modelCollector, ILoadAsset iLoadAsset, ICrossAppShareRemakeAdditionBaseModel additionModel) { }
	// RVA: 0x2bbee30 VA: 0x75951d6e30
	public Void PlayShowAnim() { }
	// RVA: 0x2bbe04c VA: 0x75951d604c
	public Void SetRemakeGroupShow(Boolean isShow) { }
	// RVA: 0x2bc1684 VA: 0x75951d9684
	private Void _EnsureCanvasGroupBlockRaycastFalse() { }
	// RVA: 0x2bc16fc VA: 0x75951d96fc
	public Void .ctor() { }
}
```