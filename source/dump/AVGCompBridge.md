# AVGCompBridge

**Namespace:** ` `


## Fields

- `AVGController m_context`


## Methods

- `AVGSceneEffectManager TryGetSceneEffectMgr()`

- `Void AbortRemainingCommands()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AVGCompBridge : IHotfixable
{
	private AVGController m_context; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_TryGetSceneEffectMgr; // 0x8
	private static DelegateBridge __Hotfix0_AbortRemainingCommands; // 0x10


	// RVA: 0x3e523d0 VA: 0x759646a3d0
	public Void .ctor(AVGController context) { }
	// RVA: 0x3e52464 VA: 0x759646a464
	public AVGSceneEffectManager TryGetSceneEffectMgr() { }
	// RVA: 0x3e524d8 VA: 0x759646a4d8
	public Void AbortRemainingCommands() { }
}
```