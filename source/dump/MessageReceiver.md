# MessageReceiver

**Namespace:** ` `


## Fields

- `StageButtonHolderPlugin m_closure`


## Methods

- `Void OnInit(StageButtonOnMapHolder)`

- `Void OnRenderStage(StageViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MessageReceiver : IMessageReceiver, IHotfixable
{
	private StageButtonHolderPlugin m_closure; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRenderStage; // 0x10


	// RVA: 0x2fa0ec0 VA: 0x75955b8ec0
	public Void .ctor(StageButtonHolderPlugin closure) { }
	// RVA: 0x2fa1370 VA: 0x75955b9370
	public Void OnInit(StageButtonOnMapHolder holder) { }
	// RVA: 0x2fa13f8 VA: 0x75955b93f8
	public Void OnRenderStage(StageViewModel model) { }
}
```