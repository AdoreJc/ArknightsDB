## SpType
|enum|name|description|
|----|----|----|
|0|INCREASE_WITH_TIME|自动回复|
|1|INCREASE_WHEN_ATTACK|攻击回复|
|2|INCREASE_WHEN_TAKEN_DAMAGE|受击回复|
|6|NEVER_USE|不使用？|
|7|E_NUM|？？|

```C#
// Dll : Torappu.Common.dll
// Namespace: Torappu
public enum SpType
{
	public Int32 value__; // 0x10
	public const SpType NONE = 0; // 0x0
	public const SpType INCREASE_WITH_TIME = 1; // 0x0
	public const SpType INCREASE_WHEN_ATTACK = 2; // 0x0
	public const SpType INCREASE_WHEN_TAKEN_DAMAGE = 4; // 0x0
	public const SpType ATTACK_OR_DAMAGE = 6; // 0x0
	public const SpType ALL = 7; // 0x0
}
```

## SpTypeIndex
|enum|name|description|
|----|----|----|
|0|INCREASE_WITH_TIME|自动回复|
|1|INCREASE_WHEN_ATTACK|攻击回复|
|2|INCREASE_WHEN_TAKEN_DAMAGE|受击回复|
|3|NEVER_USE|不使用？|
|4|E_NUM|？？|

```C#
// Dll : Torappu.Common.dll
// Namespace: Torappu
public enum SpTypeIndex
{
	public Int32 value__; // 0x10
	public const SpTypeIndex INCREASE_WITH_TIME = 0; // 0x0
	public const SpTypeIndex INCREASE_WHEN_ATTACK = 1; // 0x0
	public const SpTypeIndex INCREASE_WHEN_TAKEN_DAMAGE = 2; // 0x0
	public const SpTypeIndex NEVER_USE = 3; // 0x0
	public const SpTypeIndex E_NUM = 4; // 0x0
}
```