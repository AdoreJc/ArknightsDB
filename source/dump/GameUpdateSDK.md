# GameUpdateSDK

**Namespace:** ` `


## Fields

- `Options m_options`

- `IGameUpdateInterface m_sdkImpl`

- `Boolean m_hasUpdateAlerted`


## Methods

- `IEnumerator DoUpdate(Result)`

- `IEnumerator _UpdateGame(Context)`

- `IEnumerator _DoTaskUpdating(Context)`

- `IEnumerator _YieldCheckNetUsagePolicy(Int64)`

- `IEnumerator _WaitForTaskCancel(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GameUpdateSDK : IHotfixable
{
	private const Single COOLDOWN_INSTALL; // 0x0
	private const Int32 ERROR_CODE_NETWORK; // 0x0
	private Options m_options; // 0x10
	private IGameUpdateInterface m_sdkImpl; // 0x30
	private Boolean m_hasUpdateAlerted; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_DoUpdate; // 0x8
	private static DelegateBridge __Hotfix0__UpdateGame; // 0x10
	private static DelegateBridge __Hotfix0__DoTaskUpdating; // 0x18
	private static DelegateBridge __Hotfix0__YieldCheckNetUsagePolicy; // 0x20
	private static DelegateBridge __Hotfix0__WaitForTaskCancel; // 0x28


	// RVA: 0x27c32b4 VA: 0x7594ddb2b4
	public Void .ctor(Options options) { }
	// RVA: 0x27c33e8 VA: 0x7594ddb3e8
	public IEnumerator DoUpdate(Result result) { }
	// RVA: 0x27c34e0 VA: 0x7594ddb4e0
	private IEnumerator _UpdateGame(Context context) { }
	// RVA: 0x27c35d8 VA: 0x7594ddb5d8
	private IEnumerator _DoTaskUpdating(Context context) { }
	// RVA: 0x27c36d0 VA: 0x7594ddb6d0
	private IEnumerator _YieldCheckNetUsagePolicy(Int64 downloadSize) { }
	// RVA: 0x27c37bc VA: 0x7594ddb7bc
	private IEnumerator _WaitForTaskCancel(Int64 taskId) { }
}
```