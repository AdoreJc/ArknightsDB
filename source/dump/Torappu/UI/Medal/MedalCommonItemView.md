# MedalCommonItemView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalCommonItemAbleToGetView _ableToGetView`

- `MedalCommonItemAlreadyGetView _alreadyGetView`

- `MedalCommonItemNotGetView _notGetView`

- `CanvasGroup _alphaHandler`

- `UIMedalEvent clickEvent`

- `MedalCommonViewModel m_viewModel`


## Methods

- `Void AsyncSetData(AsyncParam)`

- `Void AsyncShow()`

- `Void Render(MedalCommonViewModel, Boolean, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalCommonItemView : MonoBehaviour, IHotfixable, IAsyncDataView`1, IAsyncShowEffect
{
	private MedalCommonItemAbleToGetView _ableToGetView; // 0x18
	private MedalCommonItemAlreadyGetView _alreadyGetView; // 0x20
	private MedalCommonItemNotGetView _notGetView; // 0x28
	private CanvasGroup _alphaHandler; // 0x30
	public UIMedalEvent clickEvent; // 0x38
	private MedalCommonViewModel m_viewModel; // 0x40
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x0
	private static DelegateBridge __Hotfix0_AsyncShow; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2799094 VA: 0x7594db1094
	public Void AsyncSetData(AsyncParam param) { }
	// RVA: 0x2799330 VA: 0x7594db1330
	public Void AsyncShow() { }
	// RVA: 0x2799148 VA: 0x7594db1148
	public Void Render(MedalCommonViewModel viewModel, Boolean ableToGetFlag, String pageName) { }
	// RVA: 0x2799408 VA: 0x7594db1408
	public Void OnClick() { }
	// RVA: 0x27994a0 VA: 0x7594db14a0
	public Void .ctor() { }
}
```