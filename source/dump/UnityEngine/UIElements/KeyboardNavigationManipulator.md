# KeyboardNavigationManipulator

**Namespace:** `UnityEngine.UIElements`


## Methods

- `Void OnRuntimeKeyDown(KeyDownEvent)`

- `Void OnEditorKeyDown(KeyDownEvent)`

- `Void OnNavigationCancel(NavigationCancelEvent)`

- `Void OnNavigationSubmit(NavigationSubmitEvent)`

- `Void OnNavigationMove(NavigationMoveEvent)`

- `Void Invoke(KeyboardNavigationOperation, EventBase)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class KeyboardNavigationManipulator : Manipulator
{
	private readonly Action`2 m_Action; // 0x18


	// RVA: 0x693cc20 VA: 0x7598f54c20
	public Void .ctor(Action`2 action) { }
	// RVA: 0x693cc58 VA: 0x7598f54c58
	protected override Void RegisterCallbacksOnTarget() { }
	// RVA: 0x693ce6c VA: 0x7598f54e6c
	protected override Void UnregisterCallbacksFromTarget() { }
	// RVA: 0x693d080 VA: 0x7598f55080
	internal Void OnKeyDown(KeyDownEvent evt) { }
	// RVA: 0x693d1b0 VA: 0x7598f551b0
	private Void OnRuntimeKeyDown(KeyDownEvent evt) { }
	// RVA: 0x693d160 VA: 0x7598f55160
	private Void OnEditorKeyDown(KeyDownEvent evt) { }
	// RVA: 0x693d3d0 VA: 0x7598f553d0
	private Void OnNavigationCancel(NavigationCancelEvent evt) { }
	// RVA: 0x693d3f4 VA: 0x7598f553f4
	private Void OnNavigationSubmit(NavigationSubmitEvent evt) { }
	// RVA: 0x693d418 VA: 0x7598f55418
	private Void OnNavigationMove(NavigationMoveEvent evt) { }
	// RVA: 0x693d2bc VA: 0x7598f552bc
	private Void Invoke(KeyboardNavigationOperation operation, EventBase evt) { }
	// RVA: 0x693d200 VA: 0x7598f55200
	internal static KeyboardNavigationOperation <OnRuntimeKeyDown>g__GetOperation|5_0(ref <>c__DisplayClass5_0 ) { }
	// RVA: 0x693d2dc VA: 0x7598f552dc
	internal static KeyboardNavigationOperation <OnEditorKeyDown>g__GetOperation|6_0(ref <>c__DisplayClass6_0 ) { }
}
```