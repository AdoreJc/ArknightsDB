# TeamSceneStartRet

**Namespace:** ` `


## Fields

- `RetCode retCode`

- `STSceneInfo sceneInfo`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TeamSceneStartRet : Protocol
{
	public const UInt32 ID; // 0x0
	public RetCode retCode; // 0x14
	public STSceneInfo sceneInfo; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x359cfbc VA: 0x7595bb4fbc
	public Void .ctor() { }
	// RVA: 0x359d030 VA: 0x7595bb5030
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x359d2bc VA: 0x7595bb52bc
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```