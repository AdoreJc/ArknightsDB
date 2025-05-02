# DuelSceneJoinDn

**Namespace:** ` `


## Fields

- `EnemyDuelProtocolRetCode retCode`

- `EnemyDuelServiceSceneJoinData data`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DuelSceneJoinDn : Protocol
{
	public const Int32 ID; // 0x0
	public EnemyDuelProtocolRetCode retCode; // 0x14
	public EnemyDuelServiceSceneJoinData data; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x29b41e8 VA: 0x7594fcc1e8
	public Void .ctor() { }
	// RVA: 0x29b425c VA: 0x7594fcc25c
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x29b43dc VA: 0x7594fcc3dc
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```