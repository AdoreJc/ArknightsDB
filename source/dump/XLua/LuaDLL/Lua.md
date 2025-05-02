# Lua

**Namespace:** `XLua.LuaDLL`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua.LuaDLL
public class Lua
{
	private const String LUADLL; // 0x0


	// RVA: 0x3ff3518 VA: 0x759660b518
	public static extern IntPtr lua_tothread(IntPtr L, Int32 index) { }
	// RVA: 0x3ffe738 VA: 0x7596616738
	public static extern Int32 xlua_get_lib_version() { }
	// RVA: 0x3ffe7a0 VA: 0x75966167a0
	public static extern Int32 lua_gc(IntPtr L, LuaGCOptions what, Int32 data) { }
	// RVA: 0x3ff6950 VA: 0x759660e950
	public static extern IntPtr lua_getupvalue(IntPtr L, Int32 funcindex, Int32 n) { }
	// RVA: 0x3ff69f0 VA: 0x759660e9f0
	public static extern IntPtr lua_setupvalue(IntPtr L, Int32 funcindex, Int32 n) { }
	// RVA: 0x3ffe834 VA: 0x7596616834
	public static extern Int32 lua_pushthread(IntPtr L) { }
	// RVA: 0x3fecb54 VA: 0x7596604b54
	public static Boolean lua_isfunction(IntPtr L, Int32 stackPos) { }
	// RVA: 0x3ffe8b0 VA: 0x75966168b0
	public static Boolean lua_islightuserdata(IntPtr L, Int32 stackPos) { }
	// RVA: 0x3fec684 VA: 0x7596604684
	public static Boolean lua_istable(IntPtr L, Int32 stackPos) { }
	// RVA: 0x3ff3500 VA: 0x759660b500
	public static Boolean lua_isthread(IntPtr L, Int32 stackPos) { }
	// RVA: 0x3fe9624 VA: 0x7596601624
	public static Int32 luaL_error(IntPtr L, String message) { }
	// RVA: 0x3ffdef0 VA: 0x7596615ef0
	public static extern Int32 lua_setfenv(IntPtr L, Int32 stackPos) { }
	// RVA: 0x3ffe968 VA: 0x7596616968
	public static extern IntPtr luaL_newstate() { }
	// RVA: 0x3ffe9d0 VA: 0x75966169d0
	public static extern Void lua_close(IntPtr L) { }
	// RVA: 0x3ffea4c VA: 0x7596616a4c
	public static extern Void luaopen_xlua(IntPtr L) { }
	// RVA: 0x3ffeac8 VA: 0x7596616ac8
	public static extern Void luaL_openlibs(IntPtr L) { }
	// RVA: 0x3ff0084 VA: 0x7596608084
	public static extern UInt32 xlua_objlen(IntPtr L, Int32 stackPos) { }
	// RVA: 0x3ff85ac VA: 0x75966105ac
	public static extern Void lua_createtable(IntPtr L, Int32 narr, Int32 nrec) { }
	// RVA: 0x3ff69e4 VA: 0x759660e9e4
	public static Void lua_newtable(IntPtr L) { }
	// RVA: 0x3ffeb44 VA: 0x7596616b44
	public static extern Int32 xlua_getglobal(IntPtr L, String name) { }
	// RVA: 0x3ffe170 VA: 0x7596616170
	public static extern Int32 xlua_setglobal(IntPtr L, String name) { }
	// RVA: 0x3ffebe4 VA: 0x7596616be4
	public static extern Void xlua_getloaders(IntPtr L) { }
	// RVA: 0x3ff6ec4 VA: 0x759660eec4
	public static extern Void lua_settop(IntPtr L, Int32 newTop) { }
	// RVA: 0x3ff02b8 VA: 0x75966082b8
	public static Void lua_pop(IntPtr L, Int32 amount) { }
	// RVA: 0x3ffec60 VA: 0x7596616c60
	public static extern Void lua_insert(IntPtr L, Int32 newTop) { }
	// RVA: 0x3ff6a84 VA: 0x759660ea84
	public static extern Void lua_remove(IntPtr L, Int32 index) { }
	// RVA: 0x3ff0220 VA: 0x7596608220
	public static extern Int32 lua_rawget(IntPtr L, Int32 index) { }
	// RVA: 0x3ff67b0 VA: 0x759660e7b0
	public static extern Void lua_rawset(IntPtr L, Int32 index) { }
	// RVA: 0x3ff8184 VA: 0x7596610184
	public static extern Int32 lua_setmetatable(IntPtr L, Int32 objIndex) { }
	// RVA: 0x3ffece4 VA: 0x7596616ce4
	public static extern Int32 lua_rawequal(IntPtr L, Int32 index1, Int32 index2) { }
	// RVA: 0x3feefe0 VA: 0x7596606fe0
	public static extern Void lua_pushvalue(IntPtr L, Int32 index) { }
	// RVA: 0x3ffed78 VA: 0x7596616d78
	public static extern Void lua_pushcclosure(IntPtr L, IntPtr fn, Int32 n) { }
	// RVA: 0x3ffee0c VA: 0x7596616e0c
	public static extern Void lua_replace(IntPtr L, Int32 index) { }
	// RVA: 0x3feb164 VA: 0x7596603164
	public static extern Int32 lua_gettop(IntPtr L) { }
	// RVA: 0x3fec69c VA: 0x759660469c
	public static extern LuaTypes lua_type(IntPtr L, Int32 index) { }
	// RVA: 0x3fec66c VA: 0x759660466c
	public static Boolean lua_isnil(IntPtr L, Int32 index) { }
	// RVA: 0x3ffee90 VA: 0x7596616e90
	public static extern Boolean lua_isnumber(IntPtr L, Int32 index) { }
	// RVA: 0x3ffef18 VA: 0x7596616f18
	public static Boolean lua_isboolean(IntPtr L, Int32 index) { }
	// RVA: 0x3ffef30 VA: 0x7596616f30
	public static extern Int32 luaL_ref(IntPtr L, Int32 registryIndex) { }
	// RVA: 0x3fef064 VA: 0x7596607064
	public static Int32 luaL_ref(IntPtr L) { }
	// RVA: 0x3ff8518 VA: 0x7596610518
	public static extern Void xlua_rawgeti(IntPtr L, Int32 tableIndex, Int64 index) { }
	// RVA: 0x3ffefb4 VA: 0x7596616fb4
	public static extern Void xlua_rawseti(IntPtr L, Int32 tableIndex, Int64 index) { }
	// RVA: 0x3fff048 VA: 0x7596617048
	public static Void lua_getref(IntPtr L, Int32 reference) { }
	// RVA: 0x3fff074 VA: 0x7596617074
	public static extern Int32 pcall_prepare(IntPtr L, Int32 error_func_ref, Int32 func_ref) { }
	// RVA: 0x3fff108 VA: 0x7596617108
	public static extern Void luaL_unref(IntPtr L, Int32 registryIndex, Int32 reference) { }
	// RVA: 0x3fff19c VA: 0x759661719c
	public static Void lua_unref(IntPtr L, Int32 reference) { }
	// RVA: 0x3fff1c8 VA: 0x75966171c8
	public static extern Boolean lua_isstring(IntPtr L, Int32 index) { }
	// RVA: 0x3feed14 VA: 0x7596606d14
	public static extern Boolean lua_isinteger(IntPtr L, Int32 index) { }
	// RVA: 0x3ff0f28 VA: 0x7596608f28
	public static extern Void lua_pushnil(IntPtr L) { }
	// RVA: 0x3ff7f08 VA: 0x759660ff08
	public static Void lua_pushstdcallcfunction(IntPtr L, lua_CSFunction function, Int32 n) { }
	// RVA: 0x3ff7094 VA: 0x759660f094
	public static extern Int32 xlua_upvalueindex(Int32 n) { }
	// RVA: 0x3ffdf74 VA: 0x7596615f74
	public static extern Int32 lua_pcall(IntPtr L, Int32 nArgs, Int32 nResults, Int32 errfunc) { }
	// RVA: 0x3fee508 VA: 0x7596606508
	public static extern Double lua_tonumber(IntPtr L, Int32 index) { }
	// RVA: 0x3fedf34 VA: 0x7596605f34
	public static extern Int32 xlua_tointeger(IntPtr L, Int32 index) { }
	// RVA: 0x3fee240 VA: 0x7596606240
	public static extern UInt32 xlua_touint(IntPtr L, Int32 index) { }
	// RVA: 0x3fee714 VA: 0x7596606714
	public static extern Boolean lua_toboolean(IntPtr L, Int32 index) { }
	// RVA: 0x3fff2e4 VA: 0x75966172e4
	public static extern IntPtr lua_topointer(IntPtr L, Int32 index) { }
	// RVA: 0x3fff368 VA: 0x7596617368
	public static extern IntPtr lua_tolstring(IntPtr L, Int32 index, out IntPtr strLen) { }
	// RVA: 0x3feb7b0 VA: 0x75966037b0
	public static String lua_tostring(IntPtr L, Int32 index) { }
	// RVA: 0x3fff3fc VA: 0x75966173fc
	public static extern IntPtr lua_atpanic(IntPtr L, lua_CSFunction panicf) { }
	// RVA: 0x3ff0194 VA: 0x7596608194
	public static extern Void lua_pushnumber(IntPtr L, Double number) { }
	// RVA: 0x3ff8c4c VA: 0x7596610c4c
	public static extern Void lua_pushboolean(IntPtr L, Boolean value) { }
	// RVA: 0x3ff8b64 VA: 0x7596610b64
	public static extern Void xlua_pushinteger(IntPtr L, Int32 value) { }
	// RVA: 0x3fff488 VA: 0x7596617488
	public static extern Void xlua_pushuint(IntPtr L, UInt32 value) { }
	// RVA: 0x3ff8be8 VA: 0x7596610be8
	public static Void lua_pushstring(IntPtr L, String str) { }
	// RVA: 0x3fff50c VA: 0x759661750c
	public static extern Void xlua_pushlstring(IntPtr L, Byte[] str, Int32 size) { }
	// RVA: 0x3ff0724 VA: 0x7596608724
	public static Void xlua_pushasciistring(IntPtr L, String str) { }
	// RVA: 0x3fff5a8 VA: 0x75966175a8
	public static Void lua_pushstring(IntPtr L, Byte[] str) { }
	// RVA: 0x3fee840 VA: 0x7596606840
	public static Byte[] lua_tobytes(IntPtr L, Int32 index) { }
	// RVA: 0x3ff7a14 VA: 0x759660fa14
	public static extern Int32 luaL_newmetatable(IntPtr L, String meta) { }
	// RVA: 0x3ff938c VA: 0x759661138c
	public static extern Int32 xlua_pgettable(IntPtr L, Int32 idx) { }
	// RVA: 0x3fff5b8 VA: 0x75966175b8
	public static extern Int32 xlua_psettable(IntPtr L, Int32 idx) { }
	// RVA: 0x3ff6ea4 VA: 0x759660eea4
	public static Void luaL_getmetatable(IntPtr L, String meta) { }
	// RVA: 0x3fff63c VA: 0x759661763c
	public static extern Int32 xluaL_loadbuffer(IntPtr L, Byte[] buff, Int32 size, String name) { }
	// RVA: 0x3ffde84 VA: 0x7596615e84
	public static Int32 luaL_loadbuffer(IntPtr L, String buff, String name) { }
	// RVA: 0x3fff700 VA: 0x7596617700
	public static extern Int32 xlua_tocsobj_safe(IntPtr L, Int32 obj) { }
	// RVA: 0x3fff784 VA: 0x7596617784
	public static extern Int32 xlua_tocsobj_fast(IntPtr L, Int32 obj) { }
	// RVA: 0x3ffdedc VA: 0x7596615edc
	public static Int32 lua_error(IntPtr L) { }
	// RVA: 0x3ff0108 VA: 0x7596608108
	public static extern Boolean lua_checkstack(IntPtr L, Int32 extra) { }
	// RVA: 0x3ff0fa4 VA: 0x7596608fa4
	public static extern Int32 lua_next(IntPtr L, Int32 index) { }
	// RVA: 0x3ff7b1c VA: 0x759660fb1c
	public static extern Void lua_pushlightuserdata(IntPtr L, IntPtr udata) { }
	// RVA: 0x3ff7ab4 VA: 0x759660fab4
	public static extern IntPtr xlua_tag() { }
	// RVA: 0x3fff884 VA: 0x7596617884
	public static extern Void luaL_where(IntPtr L, Int32 level) { }
	// RVA: 0x3fff908 VA: 0x7596617908
	public static extern Int32 xlua_tryget_cachedud(IntPtr L, Int32 key, Int32 cache_ref) { }
	// RVA: 0x3fff99c VA: 0x759661799c
	public static extern Void xlua_pushcsobj(IntPtr L, Int32 key, Int32 meta_ref, Boolean need_cache, Int32 cache_ref) { }
	// RVA: 0x3ff7f94 VA: 0x759660ff94
	public static extern Int32 gen_obj_indexer(IntPtr L) { }
	// RVA: 0x3ff8010 VA: 0x7596610010
	public static extern Int32 gen_obj_newindexer(IntPtr L) { }
	// RVA: 0x3ff808c VA: 0x759661008c
	public static extern Int32 gen_cls_indexer(IntPtr L) { }
	// RVA: 0x3ff8108 VA: 0x7596610108
	public static extern Int32 gen_cls_newindexer(IntPtr L) { }
	// RVA: 0x3fffa48 VA: 0x7596617a48
	public static extern Int32 get_error_func_ref(IntPtr L) { }
	// RVA: 0x3fffac4 VA: 0x7596617ac4
	public static extern Int32 load_error_func(IntPtr L, Int32 Ref) { }
	// RVA: 0x3fffb48 VA: 0x7596617b48
	public static extern Int32 luaopen_i64lib(IntPtr L) { }
	// RVA: 0x3fffbc4 VA: 0x7596617bc4
	public static extern Int32 luaopen_socket_core(IntPtr L) { }
	// RVA: 0x3fffc40 VA: 0x7596617c40
	public static extern Void lua_pushint64(IntPtr L, Int64 n) { }
	// RVA: 0x3fffcc4 VA: 0x7596617cc4
	public static extern Void lua_pushuint64(IntPtr L, UInt64 n) { }
	// RVA: 0x3fec914 VA: 0x7596604914
	public static extern Boolean lua_isint64(IntPtr L, Int32 idx) { }
	// RVA: 0x3fec9e8 VA: 0x75966049e8
	public static extern Boolean lua_isuint64(IntPtr L, Int32 idx) { }
	// RVA: 0x3fee330 VA: 0x7596606330
	public static extern Int64 lua_toint64(IntPtr L, Int32 idx) { }
	// RVA: 0x3fee420 VA: 0x7596606420
	public static extern UInt64 lua_touint64(IntPtr L, Int32 idx) { }
	// RVA: 0x3fff250 VA: 0x7596617250
	public static extern Void xlua_push_csharp_function(IntPtr L, IntPtr fn, Int32 n) { }
	// RVA: 0x3ffe8c8 VA: 0x75966168c8
	public static extern Int32 xlua_csharp_str_error(IntPtr L, String message) { }
	// RVA: 0x3fff808 VA: 0x7596617808
	public static extern Int32 xlua_csharp_error(IntPtr L) { }
	// RVA: 0x3fffd48 VA: 0x7596617d48
	public static extern Boolean xlua_pack_int8_t(IntPtr buff, Int32 offset, Byte field) { }
	// RVA: 0x3fffde0 VA: 0x7596617de0
	public static extern Boolean xlua_unpack_int8_t(IntPtr buff, Int32 offset, out Byte field) { }
	// RVA: 0x3fffe7c VA: 0x7596617e7c
	public static extern Boolean xlua_pack_int16_t(IntPtr buff, Int32 offset, Int16 field) { }
	// RVA: 0x3ffff18 VA: 0x7596617f18
	public static extern Boolean xlua_unpack_int16_t(IntPtr buff, Int32 offset, out Int16 field) { }
	// RVA: 0x3ffffb4 VA: 0x7596617fb4
	public static extern Boolean xlua_pack_int32_t(IntPtr buff, Int32 offset, Int32 field) { }
	// RVA: 0x4000050 VA: 0x7596618050
	public static extern Boolean xlua_unpack_int32_t(IntPtr buff, Int32 offset, out Int32 field) { }
	// RVA: 0x40000ec VA: 0x75966180ec
	public static extern Boolean xlua_pack_int64_t(IntPtr buff, Int32 offset, Int64 field) { }
	// RVA: 0x4000188 VA: 0x7596618188
	public static extern Boolean xlua_unpack_int64_t(IntPtr buff, Int32 offset, out Int64 field) { }
	// RVA: 0x4000224 VA: 0x7596618224
	public static extern Boolean xlua_pack_float(IntPtr buff, Int32 offset, Single field) { }
	// RVA: 0x40002c0 VA: 0x75966182c0
	public static extern Boolean xlua_unpack_float(IntPtr buff, Int32 offset, out Single field) { }
	// RVA: 0x400035c VA: 0x759661835c
	public static extern Boolean xlua_pack_double(IntPtr buff, Int32 offset, Double field) { }
	// RVA: 0x40003f8 VA: 0x75966183f8
	public static extern Boolean xlua_unpack_double(IntPtr buff, Int32 offset, out Double field) { }
	// RVA: 0x4000494 VA: 0x7596618494
	public static extern IntPtr xlua_pushstruct(IntPtr L, UInt32 size, Int32 meta_ref) { }
	// RVA: 0x4000528 VA: 0x7596618528
	public static extern Void xlua_pushcstable(IntPtr L, UInt32 field_count, Int32 meta_ref) { }
	// RVA: 0x3fee9c0 VA: 0x75966069c0
	public static extern IntPtr lua_touserdata(IntPtr L, Int32 idx) { }
	// RVA: 0x40005b8 VA: 0x75966185b8
	public static extern Int32 xlua_gettypeid(IntPtr L, Int32 idx) { }
	// RVA: 0x400063c VA: 0x759661863c
	public static extern Int32 xlua_get_registry_index() { }
	// RVA: 0x40006a4 VA: 0x75966186a4
	public static extern Int32 xlua_pgettable_bypath(IntPtr L, Int32 idx, String path) { }
	// RVA: 0x4000754 VA: 0x7596618754
	public static extern Int32 xlua_psettable_bypath(IntPtr L, Int32 idx, String path) { }
	// RVA: 0x4000804 VA: 0x7596618804
	public static extern Boolean xlua_pack_float2(IntPtr buff, Int32 offset, Single f1, Single f2) { }
	// RVA: 0x40008a8 VA: 0x75966188a8
	public static extern Boolean xlua_unpack_float2(IntPtr buff, Int32 offset, out Single f1, out Single f2) { }
	// RVA: 0x400094c VA: 0x759661894c
	public static extern Boolean xlua_pack_float3(IntPtr buff, Int32 offset, Single f1, Single f2, Single f3) { }
	// RVA: 0x4000a00 VA: 0x7596618a00
	public static extern Boolean xlua_unpack_float3(IntPtr buff, Int32 offset, out Single f1, out Single f2, out Single f3) { }
	// RVA: 0x4000ab4 VA: 0x7596618ab4
	public static extern Boolean xlua_pack_float4(IntPtr buff, Int32 offset, Single f1, Single f2, Single f3, Single f4) { }
	// RVA: 0x4000b70 VA: 0x7596618b70
	public static extern Boolean xlua_unpack_float4(IntPtr buff, Int32 offset, out Single f1, out Single f2, out Single f3, out Single f4) { }
	// RVA: 0x4000c2c VA: 0x7596618c2c
	public static extern Boolean xlua_pack_float5(IntPtr buff, Int32 offset, Single f1, Single f2, Single f3, Single f4, Single f5) { }
	// RVA: 0x4000cf8 VA: 0x7596618cf8
	public static extern Boolean xlua_unpack_float5(IntPtr buff, Int32 offset, out Single f1, out Single f2, out Single f3, out Single f4, out Single f5) { }
	// RVA: 0x4000dc4 VA: 0x7596618dc4
	public static extern Boolean xlua_pack_float6(IntPtr buff, Int32 offset, Single f1, Single f2, Single f3, Single f4, Single f5, Single f6) { }
	// RVA: 0x4000e98 VA: 0x7596618e98
	public static extern Boolean xlua_unpack_float6(IntPtr buff, Int32 offset, out Single f1, out Single f2, out Single f3, out Single f4, out Single f5, out Single f6) { }
	// RVA: 0x4000f6c VA: 0x7596618f6c
	public static extern Boolean xlua_pack_decimal(IntPtr buff, Int32 offset, ref Decimal dec) { }
	// RVA: 0x4001008 VA: 0x7596619008
	public static extern Boolean xlua_unpack_decimal(IntPtr buff, Int32 offset, out Byte scale, out Byte sign, out Int32 hi32, out UInt64 lo64) { }
	// RVA: 0x40010c4 VA: 0x75966190c4
	public static Boolean xlua_is_eq_str(IntPtr L, Int32 index, String str) { }
	// RVA: 0x40010dc VA: 0x75966190dc
	public static extern Boolean xlua_is_eq_str(IntPtr L, Int32 index, String str, Int32 str_len) { }
	// RVA: 0x3ff1a60 VA: 0x7596609a60
	public static extern IntPtr xlua_gl(IntPtr L) { }
	// RVA: 0x4001198 VA: 0x7596619198
	public static extern Int32 luaopen_rapidjson(IntPtr L) { }
	// RVA: 0x3ffe728 VA: 0x7596616728
	public static Int32 LoadRapidJson(IntPtr L) { }
	// RVA: 0x4001214 VA: 0x7596619214
	public static extern Int32 luaopen_lpeg(IntPtr L) { }
	// RVA: 0x3ffe72c VA: 0x759661672c
	public static Int32 LoadLpeg(IntPtr L) { }
	// RVA: 0x4001290 VA: 0x7596619290
	public static extern Int32 luaopen_pb(IntPtr L) { }
	// RVA: 0x3ffe730 VA: 0x7596616730
	public static Int32 LoadLuaProfobuf(IntPtr L) { }
	// RVA: 0x400130c VA: 0x759661930c
	public static extern Int32 luaopen_ffi(IntPtr L) { }
	// RVA: 0x3ffe734 VA: 0x7596616734
	public static Int32 LoadFFI(IntPtr L) { }
	// RVA: 0x4001388 VA: 0x7596619388
	public Void .ctor() { }
}
```