# CharacterTransHomeState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _viewProto`

- `GameObject _resultViewProto`

- `Transform _viewContainer`

- `Image _blackCover`

- `GameObject _backButtonPanel`

- `CharacterTransView m_transView`

- `CharacterTransResultView m_transResultView`

- `RenderTexture m_rt`

- `Coroutine m_resultDisplayCoroutine`

- `Coroutine m_introCoroutine`

- `Coroutine m_outroCoroutine`


## Methods

- `IEnumerator _IntroCoroutine()`

- `IEnumerator _OutroCoroutine()`

- `IEnumerator _ResultDisplayCoroutine(CharUISkinStruct, Int32)`

- `Int32 _GetCurrentTransIndex(Param)`

- `TrainingParseResult _ParseTrainingInfo(Int32)`

- `String OnFocusTmpl(Int32)`

- `Void OnClickTmpl(Int32)`

- `Void OnDestroy()`

- `Void OnBackButtonPressed()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterTransHomeState : State
{
	private GameObject _viewProto; // 0x50
	private GameObject _resultViewProto; // 0x58
	private Transform _viewContainer; // 0x60
	private Image _blackCover; // 0x68
	private GameObject _backButtonPanel; // 0x70
	private CharacterTransView m_transView; // 0x78
	private CharacterTransResultView m_transResultView; // 0x80
	private RenderTexture m_rt; // 0x88
	private Coroutine m_resultDisplayCoroutine; // 0x90
	private Coroutine m_introCoroutine; // 0x98
	private Coroutine m_outroCoroutine; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__IntroCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__OutroCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__ResultDisplayCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__GetCurrentTransIndex; // 0x20
	private static DelegateBridge __Hotfix0__ParseTrainingInfo; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnFocusTmpl; // 0x38
	private static DelegateBridge __Hotfix0_OnClickTmpl; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge __Hotfix0_OnBackButtonPressed; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2d50a68 VA: 0x7595368a68
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d50acc VA: 0x7595368acc
	private IEnumerator _IntroCoroutine() { }
	// RVA: 0x2d50ba0 VA: 0x7595368ba0
	private IEnumerator _OutroCoroutine() { }
	// RVA: 0x2d50c74 VA: 0x7595368c74
	private IEnumerator _ResultDisplayCoroutine(CharUISkinStruct skin, Int32 transIndex) { }
	// RVA: 0x2d50d90 VA: 0x7595368d90
	private Int32 _GetCurrentTransIndex(Param param) { }
	// RVA: 0x2d50f24 VA: 0x7595368f24
	private TrainingParseResult _ParseTrainingInfo(Int32 charInstId) { }
	// RVA: 0x2d51668 VA: 0x7595369668
	protected override Void OnEnter() { }
	// RVA: 0x2d51dc4 VA: 0x7595369dc4
	private String OnFocusTmpl(Int32 idx) { }
	// RVA: 0x2d521e8 VA: 0x759536a1e8
	private Void OnClickTmpl(Int32 idx) { }
	// RVA: 0x2d52604 VA: 0x759536a604
	private Void OnDestroy() { }
	// RVA: 0x2d526cc VA: 0x759536a6cc
	public Void OnBackButtonPressed() { }
	// RVA: 0x2d5276c VA: 0x759536a76c
	public Void .ctor() { }
	// RVA: 0x2d527dc VA: 0x759536a7dc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```