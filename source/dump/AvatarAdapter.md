# AvatarAdapter

**Namespace:** ` `


## Fields

- `EnemyDuelPerformView m_closure`

- `EnemyDuelChoiceSide m_side`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AvatarAdapter : SimpleLayoutAdapter
{
	private EnemyDuelPerformView m_closure; // 0x20
	private EnemyDuelChoiceSide m_side; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x298b110 VA: 0x7594fa3110
	public Void .ctor(EnemyDuelPerformView closure, EnemyDuelChoiceSide side) { }
	// RVA: 0x298b628 VA: 0x7594fa3628
	public override Int32 get_count() { }
	// RVA: 0x298b6e8 VA: 0x7594fa36e8
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```