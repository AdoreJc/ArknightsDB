# TeamSceneStartDn

**Namespace:** ` `


## Fields

- `EnemyDuelProtocolRetCode retCode`

- `STDuelSceneInfo sceneInfo`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TeamSceneStartDn : Protocol
{
	public const Int32 ID; // 0x0
	public EnemyDuelProtocolRetCode retCode; // 0x14
	public STDuelSceneInfo sceneInfo; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x29b4e7c VA: 0x7594fcce7c
	public Void .ctor() { }
	// RVA: 0x29b4ef0 VA: 0x7594fccef0
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x29b5050 VA: 0x7594fcd050
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```