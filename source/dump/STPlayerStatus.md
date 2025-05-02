# STPlayerStatus

**Namespace:** ` `


## Fields

- `String uid`

- `SByte pos`

- `String nickName`

- `String avatarType`

- `String avatarId`

- `String secretary`

- `String secretarySkinId`

- `String nameCardSkinId`

- `Int32 nameCardSkinTmpl`

- `Boolean isMentor`

- `Int32 level`

- `Boolean settleLike`

- `TeamMemberState state`

- `Boolean offline`

- `Boolean sentBasicSquad`

- `STBasicSquad basicSquad`


## Methods

- `Void Read(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class STPlayerStatus : IStreamDeserialize
{
	public String uid; // 0x10
	public SByte pos; // 0x18
	public String nickName; // 0x20
	public String avatarType; // 0x28
	public String avatarId; // 0x30
	public String secretary; // 0x38
	public String secretarySkinId; // 0x40
	public String nameCardSkinId; // 0x48
	public Int32 nameCardSkinTmpl; // 0x50
	public List`1 title; // 0x58
	public Boolean isMentor; // 0x60
	public Int32 level; // 0x64
	public Boolean settleLike; // 0x68
	public TeamMemberState state; // 0x6c
	public Boolean offline; // 0x70
	public Boolean sentBasicSquad; // 0x71
	public STBasicSquad basicSquad; // 0x78
	public List`1 prefer; // 0x80
	public List`1 backup; // 0x88
	public List`1 backupOverlap; // 0x90
	public List`1 allocTemp; // 0x98
	public List`1 squad; // 0xa0


	// RVA: 0x35a0d94 VA: 0x7595bb8d94
	public Void Read(IStreamReader from) { }
	// RVA: 0x35a14f8 VA: 0x7595bb94f8
	public Void .ctor() { }
}
```