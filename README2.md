````
Performing configuration checks

    - default address-model    : 64-bit (cached)
    - default architecture     : x86 (cached)

Building the Boost C++ Libraries.


    - C++11 mutex              : yes (cached)
    - lockfree boost::atomic_flag : yes (cached)
    - Boost.Config Feature Check: cxx11_auto_declarations : yes (cached)
    - Boost.Config Feature Check: cxx11_constexpr : yes (cached)
    - Boost.Config Feature Check: cxx11_defaulted_functions : yes (cached)
    - Boost.Config Feature Check: cxx11_final : yes (cached)
    - Boost.Config Feature Check: cxx11_hdr_mutex : yes (cached)
    - Boost.Config Feature Check: cxx11_hdr_tuple : yes (cached)
    - Boost.Config Feature Check: cxx11_lambdas : yes (cached)
    - Boost.Config Feature Check: cxx11_noexcept : yes (cached)
    - Boost.Config Feature Check: cxx11_nullptr : yes (cached)
    - Boost.Config Feature Check: cxx11_rvalue_references : yes (cached)
    - Boost.Config Feature Check: cxx11_template_aliases : yes (cached)
    - Boost.Config Feature Check: cxx11_thread_local : yes (cached)
    - Boost.Config Feature Check: cxx11_variadic_templates : yes (cached)
    - has_icu builds           : no  (cached)
warning: Graph library does not contain MPI-based parallel components.
note: to enable them, add "using mpi ;" to your user-config.jam
    - zlib                     : no  (cached)
    - bzip2                    : no  (cached)
    - lzma                     : no  (cached)
    - zstd                     : no  (cached)
    - iconv (libc)             : yes (cached)
    - icu                      : no  (cached)
    - icu (lib64)              : no  (cached)
    - native-atomic-int32-supported : yes (cached)
    - native-syslog-supported  : yes (cached)
    - pthread-supports-robust-mutexes : yes (cached)
    - compiler-supports-ssse3  : yes (cached)
    - compiler-supports-avx2   : yes (cached)
    - gcc visibility           : yes (cached)
    - long double support      : yes (cached)
warning: skipping optional Message Passing Interface (MPI) library.
note: to enable MPI support, add "using mpi ;" to user-config.jam.
note: to suppress this message, pass "--without-mpi" to bjam.
note: otherwise, you can safely ignore this message.
    - libbacktrace builds      : yes (cached)
    - addr2line builds         : yes (cached)
    - WinDbg builds            : no  (cached)
    - WinDbgCached builds      : no  (cached)
    - BOOST_COMP_GNUC >= 4.3.0 : no  (cached)
    - zlib                     : no  (cached)
    - bzip2                    : no  (cached)
    - lzma                     : no  (cached)
    - zstd                     : no  (cached)

Component configuration:

    - atomic                   : building
    - chrono                   : building
    - container                : building
    - context                  : building
    - contract                 : building
    - coroutine                : building
    - date_time                : building
    - exception                : building
    - fiber                    : building
    - filesystem               : building
    - graph                    : building
    - graph_parallel           : building
    - iostreams                : building
    - locale                   : building
    - log                      : building
    - math                     : building
    - mpi                      : building
    - program_options          : building
    - python                   : building
    - random                   : building
    - regex                    : building
    - serialization            : building
    - stacktrace               : building
    - system                   : building
    - test                     : building
    - thread                   : building
    - timer                    : building
    - type_erasure             : building
    - wave                     : building

...patience...
...patience...
...patience...
...patience...
...patience...
...patience...
...found 14123 targets...
...updating 395 targets...
gcc.compile.c++ bin.v2/libs/type_erasure/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/dynamic_binding.o
In file included from /usr/include/pthread.h:33,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr-default.h:35,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr.h:157,
                 from /usr/include/c++/15/ext/atomicity.h:37,
                 from /usr/include/c++/15/bits/shared_ptr_base.h:61,
                 from /usr/include/c++/15/bits/shared_ptr.h:53,
                 from /usr/include/c++/15/memory:82,
                 from ./boost/config/no_tr1/memory.hpp:21,
                 from ./boost/get_pointer.hpp:14,
                 from ./boost/bind/mem_fn.hpp:25,
                 from ./boost/mem_fn.hpp:22,
                 from ./boost/bind/bind.hpp:26,
                 from ./boost/bind.hpp:22,
                 from ./boost/thread/pthread/shared_mutex.hpp:12,
                 from ./boost/thread/shared_mutex.hpp:28,
                 from libs/type_erasure/src/dynamic_binding.cpp:14:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_CHRONO_STATIC_LINK=1 -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_LIB=1 -DNDEBUG  -I"." -c -o "bin.v2/libs/type_erasure/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/dynamic_binding.o" "libs/type_erasure/src/dynamic_binding.cpp"

...failed gcc.compile.c++ bin.v2/libs/type_erasure/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/dynamic_binding.o...
...skipped <pbin.v2/libs/type_erasure/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_type_erasure.a(clean) for lack of <pbin.v2/libs/type_erasure/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>dynamic_binding.o...
...skipped <pbin.v2/libs/type_erasure/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_type_erasure.a for lack of <pbin.v2/libs/type_erasure/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>dynamic_binding.o...
...skipped <pstage/lib>libboost_type_erasure.a for lack of <pbin.v2/libs/type_erasure/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_type_erasure.a...
gcc.compile.c++ bin.v2/libs/thread/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/pthread/thread.o
In file included from /usr/include/pthread.h:33,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr-default.h:35,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr.h:157,
                 from /usr/include/c++/15/ext/atomicity.h:37,
                 from /usr/include/c++/15/bits/ios_base.h:41,
                 from /usr/include/c++/15/ios:46,
                 from /usr/include/c++/15/bits/ostream.h:43,
                 from /usr/include/c++/15/ostream:42,
                 from ./boost/system/error_code.hpp:17,
                 from ./boost/system/system_error.hpp:11,
                 from ./boost/thread/exceptions.hpp:22,
                 from ./boost/thread/pthread/thread_data.hpp:10,
                 from ./boost/thread/thread_only.hpp:17,
                 from libs/thread/src/pthread/thread.cpp:11:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~
In file included from ./boost/functional/hash.hpp:6,
                 from ./boost/thread/detail/thread.hpp:38,
                 from ./boost/thread/thread_only.hpp:22:
./boost/container_hash/hash.hpp:130:33: warning: ‘template<class _Arg, class _Result> struct std::unary_function’ is deprecated [-Wdeprecated-declarations]
  130 |         struct hash_base : std::unary_function<T, std::size_t> {};
      |                                 ^~~~~~~~~~~~~~
In file included from /usr/include/c++/15/string:51,
                 from ./boost/thread/exceptions.hpp:20:
/usr/include/c++/15/bits/stl_function.h:117:12: note: declared here
  117 |     struct unary_function
      |            ^~~~~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::constraint<Model>::failed() [with Model = boost::algorithm::FinderConcept<boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/algorithm/string/iter_find.hpp:77:13:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:47:52: warning: ‘this’ pointer is null [-Wnonnull]
   47 |     static void failed() { ((Model*)0)->constraints(); }
      |                            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/algorithm/string/iter_find.hpp:26:
./boost/algorithm/string/concept.hpp:40:18: note: in a call to non-static member function ‘void boost::algorithm::FinderConcept<FinderT, IteratorT>::constraints() [with FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >; IteratorT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   40 |             void constraints()
      |                  ^~~~~~~~~~~
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/concept_check.hpp:167:5:   required from ‘struct boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:125:16:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  125 |         struct IncrementableIteratorConcept : CopyConstructible<Iterator>
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31:
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >]’:
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/iterator/iterator_concepts.hpp:114:7:   [ skipping 18 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’:
./boost/iterator/iterator_concepts.hpp:114:7:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::incrementable_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/range/concepts.hpp:136:13:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/concept_check.hpp:233:5:   required from ‘struct boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >]’:
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:152:13:   [ skipping 17 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’:
./boost/range/concepts.hpp:152:13:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:278:9:   [ skipping 12 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::single_pass_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/range/concepts.hpp:158:13:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:278:9:   [ skipping 12 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/range/concepts.hpp:278:9:   required from ‘struct boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/algorithm/equal.hpp:174:13:   [ skipping 7 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::range_detail::SinglePassIteratorConcept<Iterator>::~SinglePassIteratorConcept() [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:158:13: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  158 |             BOOST_CONCEPT_USAGE(SinglePassIteratorConcept)
      |             ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >]’:
./boost/range/concepts.hpp:284:9:   required from ‘struct boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/algorithm/equal.hpp:174:13:   [ skipping 7 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/range/algorithm/equal.hpp:174:13:   required from ‘bool boost::range::equal(const SinglePassRange1&, const SinglePassRange2&) [with SinglePassRange1 = boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; SinglePassRange2 = boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/iterator_range_core.hpp:646:32:   required from ‘bool boost::operator==(const iterator_range<IteratorT>&, const iterator_range<Iterator2T>&) [with Iterator1T = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >; Iterator2T = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
  646 |             return boost::equal( l, r );
      |                    ~~~~~~~~~~~~^~~~~~~~
./boost/algorithm/string/find_iterator.hpp:333:32:   required from ‘bool boost::algorithm::split_iterator<IteratorT>::equal(const boost::algorithm::split_iterator<IteratorT>&) const [with IteratorT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
  333 |                         m_Match==Other.m_Match &&
      |                         ~~~~~~~^~~~~~~~~~~~~~~
./boost/iterator/iterator_facade.hpp:568:26:   required from ‘static bool boost::iterators::iterator_core_access::equal(const Facade1&, const Facade2&, mpl_::true_) [with Facade1 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; Facade2 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; mpl_::true_ = mpl_::bool_<true>]’
  568 |           return f1.equal(f2);
      |                  ~~~~~~~~^~~~
./boost/iterator/iterator_facade.hpp:900:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator==(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; V1 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; TC1 = forward_traversal_tag; Reference1 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >&; Difference1 = long int; Derived2 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; V2 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; TC2 = forward_traversal_tag; Reference2 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >&; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
./boost/iterator/iterator_adaptor.hpp:305:29:   [ skipping 2 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::SinglePassRangeConcept<T>::~SinglePassRangeConcept() [with T = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:284:9: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  284 |         BOOST_CONCEPT_USAGE(SinglePassRangeConcept)
      |         ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept_check.hpp:167:5:   required from ‘struct boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:125:16:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  125 |         struct IncrementableIteratorConcept : CopyConstructible<Iterator>
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   [ skipping 15 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::CopyConstructible<TT>::~CopyConstructible() [with TT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:167:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  167 |     BOOST_CONCEPT_USAGE(CopyConstructible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 19 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::incrementable_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/range/concepts.hpp:136:13:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::range_detail::IncrementableIteratorConcept<Iterator>::~IncrementableIteratorConcept() [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:136:13: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  136 |             BOOST_CONCEPT_USAGE(IncrementableIteratorConcept)
      |             ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept_check.hpp:233:5:   required from ‘struct boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::EqualityComparable<TT>::~EqualityComparable() [with TT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:233:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  233 |     BOOST_CONCEPT_USAGE(EqualityComparable) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 18 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::single_pass_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/range/concepts.hpp:158:13:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::range_detail::SinglePassIteratorConcept<Iterator>::~SinglePassIteratorConcept() [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:158:13: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  158 |             BOOST_CONCEPT_USAGE(SinglePassIteratorConcept)
      |             ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/range/concepts.hpp:284:9:   required from ‘struct boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 8 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::SinglePassRangeConcept<T>::~SinglePassRangeConcept() [with T = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:284:9: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  284 |         BOOST_CONCEPT_USAGE(SinglePassRangeConcept)
      |         ^~~~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -pedantic -fvisibility=hidden -Wextra -Wno-long-long -Wno-unused-parameter -Wunused-function -pedantic -DBOOST_ALL_NO_LIB=1 -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_DONT_USE_CHRONO -DBOOST_THREAD_POSIX -DNDEBUG  -I"." -c -o "bin.v2/libs/thread/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/pthread/thread.o" "libs/thread/src/pthread/thread.cpp"

...failed gcc.compile.c++ bin.v2/libs/thread/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/pthread/thread.o...
...skipped <pbin.v2/libs/thread/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.a(clean) for lack of <pbin.v2/libs/thread/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>pthread/thread.o...
...skipped <pbin.v2/libs/thread/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.a for lack of <pbin.v2/libs/thread/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>pthread/thread.o...
...skipped <pstage/lib>libboost_thread.a for lack of <pbin.v2/libs/thread/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.a...
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/posix/stack_traits.o
In file included from ./boost/coroutine/stack_traits.hpp:14,
                 from libs/coroutine/src/posix/stack_traits.cpp:7:
./boost/coroutine/detail/config.hpp:17:4: warning: #warning "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING." [-Wcpp]
   17 | #  warning                  "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING."
      |    ^~~~~~~
In file included from /usr/include/pthread.h:33,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr-default.h:35,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr.h:157,
                 from /usr/include/c++/15/ext/atomicity.h:37,
                 from /usr/include/c++/15/bits/ios_base.h:41,
                 from /usr/include/c++/15/ios:46,
                 from /usr/include/c++/15/bits/ostream.h:43,
                 from /usr/include/c++/15/ostream:42,
                 from ./boost/system/error_code.hpp:17,
                 from ./boost/system/system_error.hpp:11,
                 from ./boost/thread/exceptions.hpp:22,
                 from ./boost/thread/pthread/thread_data.hpp:10,
                 from ./boost/thread/thread_only.hpp:17,
                 from ./boost/thread/thread.hpp:12,
                 from ./boost/thread.hpp:13,
                 from libs/coroutine/src/posix/stack_traits.cpp:22:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~
In file included from ./boost/functional/hash.hpp:6,
                 from ./boost/thread/detail/thread.hpp:38,
                 from ./boost/thread/thread_only.hpp:22:
./boost/container_hash/hash.hpp:130:33: warning: ‘template<class _Arg, class _Result> struct std::unary_function’ is deprecated [-Wdeprecated-declarations]
  130 |         struct hash_base : std::unary_function<T, std::size_t> {};
      |                                 ^~~~~~~~~~~~~~
In file included from /usr/include/c++/15/string:51,
                 from ./boost/thread/exceptions.hpp:20:
/usr/include/c++/15/bits/stl_function.h:117:12: note: declared here
  117 |     struct unary_function
      |            ^~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_CHRONO_STATIC_LINK=1 -DBOOST_COROUTINES_SOURCE -DBOOST_DISABLE_ASSERTS -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_LIB=1 -DNDEBUG  -I"." -c -o "bin.v2/libs/coroutine/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/posix/stack_traits.o" "libs/coroutine/src/posix/stack_traits.cpp"

...failed gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/posix/stack_traits.o...
...skipped <pbin.v2/libs/coroutine/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_coroutine.a(clean) for lack of <pbin.v2/libs/coroutine/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>posix/stack_traits.o...
...skipped <pbin.v2/libs/coroutine/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_coroutine.a for lack of <pbin.v2/libs/coroutine/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>posix/stack_traits.o...
...skipped <pstage/lib>libboost_coroutine.a for lack of <pbin.v2/libs/coroutine/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_coroutine.a...
gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/severity_level.o
In file included from /usr/include/x86_64-linux-gnu/bits/local_lim.h:81,
                 from /usr/include/x86_64-linux-gnu/bits/posix1_lim.h:161,
                 from /usr/include/limits.h:195,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:210,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/syslimits.h:9,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:34,
                 from ./boost/log/detail/config.hpp:33,
                 from libs/log/src/severity_level.cpp:16:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~
In file included from ./boost/functional/hash.hpp:6,
                 from ./boost/thread/detail/thread.hpp:38,
                 from ./boost/thread/thread_only.hpp:22,
                 from ./boost/thread/thread.hpp:12,
                 from libs/log/src/severity_level.cpp:23:
./boost/container_hash/hash.hpp:130:33: warning: ‘template<class _Arg, class _Result> struct std::unary_function’ is deprecated [-Wdeprecated-declarations]
  130 |         struct hash_base : std::unary_function<T, std::size_t> {};
      |                                 ^~~~~~~~~~~~~~
In file included from /usr/include/c++/15/functional:51,
                 from ./boost/config/no_tr1/functional.hpp:21,
                 from ./boost/smart_ptr/intrusive_ptr.hpp:24,
                 from ./boost/log/sources/severity_feature.hpp:20,
                 from libs/log/src/severity_level.cpp:18:
/usr/include/c++/15/bits/stl_function.h:117:12: note: declared here
  117 |     struct unary_function
      |            ^~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fno-strict-aliasing -ftemplate-depth-1024 -DBOOST_ALL_NO_LIB=1 -DBOOST_ATOMIC_STATIC_LINK=1 -DBOOST_CHRONO_STATIC_LINK=1 -DBOOST_FILESYSTEM_STATIC_LINK=1 -DBOOST_LOG_BUILDING_THE_LIB=1 -DBOOST_LOG_HAS_PTHREAD_MUTEX_ROBUST -DBOOST_LOG_USE_AVX2 -DBOOST_LOG_USE_NATIVE_SYSLOG -DBOOST_LOG_USE_SSSE3 -DBOOST_LOG_WITHOUT_DEBUG_OUTPUT -DBOOST_LOG_WITHOUT_EVENT_LOG -DBOOST_SPIRIT_USE_PHOENIX_V3=1 -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_DONT_USE_CHRONO=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_LIB=1 -DDATE_TIME_INLINE -DNDEBUG -D_XOPEN_SOURCE=600 -D__STDC_CONSTANT_MACROS  -I"." -I"libs/log/src" -c -o "bin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/severity_level.o" "libs/log/src/severity_level.cpp"

...failed gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/severity_level.o...
gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/event.o
In file included from /usr/include/x86_64-linux-gnu/bits/local_lim.h:81,
                 from /usr/include/x86_64-linux-gnu/bits/posix1_lim.h:161,
                 from /usr/include/limits.h:195,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:210,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/syslimits.h:9,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:34,
                 from ./boost/log/detail/config.hpp:33,
                 from libs/log/src/event.cpp:16:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fno-strict-aliasing -ftemplate-depth-1024 -DBOOST_ALL_NO_LIB=1 -DBOOST_ATOMIC_STATIC_LINK=1 -DBOOST_CHRONO_STATIC_LINK=1 -DBOOST_FILESYSTEM_STATIC_LINK=1 -DBOOST_LOG_BUILDING_THE_LIB=1 -DBOOST_LOG_HAS_PTHREAD_MUTEX_ROBUST -DBOOST_LOG_USE_AVX2 -DBOOST_LOG_USE_NATIVE_SYSLOG -DBOOST_LOG_USE_SSSE3 -DBOOST_LOG_WITHOUT_DEBUG_OUTPUT -DBOOST_LOG_WITHOUT_EVENT_LOG -DBOOST_SPIRIT_USE_PHOENIX_V3=1 -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_DONT_USE_CHRONO=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_LIB=1 -DDATE_TIME_INLINE -DNDEBUG -D_XOPEN_SOURCE=600 -D__STDC_CONSTANT_MACROS  -I"." -I"libs/log/src" -c -o "bin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/event.o" "libs/log/src/event.cpp"

...failed gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/event.o...
...skipped <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_log.a(clean) for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>severity_level.o...
...skipped <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_log.a for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>severity_level.o...
...skipped <pstage/lib>libboost_log.a for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_log.a...
gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/setup/init_from_settings.o
In file included from /usr/include/x86_64-linux-gnu/bits/local_lim.h:81,
                 from /usr/include/x86_64-linux-gnu/bits/posix1_lim.h:161,
                 from /usr/include/limits.h:195,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:210,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/syslimits.h:9,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:34,
                 from ./boost/log/detail/config.hpp:33,
                 from ./boost/log/detail/setup_config.hpp:20,
                 from libs/log/src/setup/init_from_settings.cpp:26:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~
In file included from ./boost/functional/hash.hpp:6,
                 from ./boost/thread/detail/thread.hpp:38,
                 from ./boost/thread/thread_only.hpp:22,
                 from ./boost/thread/thread.hpp:12,
                 from ./boost/log/sinks/async_frontend.hpp:39,
                 from ./boost/log/sinks.hpp:25,
                 from libs/log/src/setup/init_from_settings.cpp:54:
./boost/container_hash/hash.hpp:130:33: warning: ‘template<class _Arg, class _Result> struct std::unary_function’ is deprecated [-Wdeprecated-declarations]
  130 |         struct hash_base : std::unary_function<T, std::size_t> {};
      |                                 ^~~~~~~~~~~~~~
In file included from /usr/include/c++/15/string:51,
                 from /usr/include/c++/15/bits/locale_classes.h:42,
                 from /usr/include/c++/15/bits/ios_base.h:43,
                 from /usr/include/c++/15/ios:46,
                 from libs/log/src/setup/init_from_settings.cpp:28:
/usr/include/c++/15/bits/stl_function.h:117:12: note: declared here
  117 |     struct unary_function
      |            ^~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fno-strict-aliasing -ftemplate-depth-1024 -DBOOST_ALL_NO_LIB=1 -DBOOST_ATOMIC_STATIC_LINK=1 -DBOOST_CHRONO_STATIC_LINK=1 -DBOOST_FILESYSTEM_STATIC_LINK=1 -DBOOST_LOG_HAS_PTHREAD_MUTEX_ROBUST -DBOOST_LOG_SETUP_BUILDING_THE_LIB=1 -DBOOST_LOG_USE_AVX2 -DBOOST_LOG_USE_NATIVE_SYSLOG -DBOOST_LOG_USE_SSSE3 -DBOOST_LOG_WITHOUT_EVENT_LOG -DBOOST_SPIRIT_USE_PHOENIX_V3=1 -DBOOST_SYSTEM_STATIC_LINK=1 -DBOOST_THREAD_BUILD_LIB=1 -DBOOST_THREAD_DONT_USE_CHRONO=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_LIB=1 -DDATE_TIME_INLINE -DNDEBUG -D_XOPEN_SOURCE=600 -D__STDC_CONSTANT_MACROS  -I"." -I"libs/log/src" -c -o "bin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/setup/init_from_settings.o" "libs/log/src/setup/init_from_settings.cpp"

...failed gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden/setup/init_from_settings.o...
...skipped <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_log_setup.a(clean) for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>setup/init_from_settings.o...
...skipped <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_log_setup.a for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>setup/init_from_settings.o...
...skipped <pstage/lib>libboost_log_setup.a for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/link-static/threadapi-pthread/threading-multi/visibility-hidden>libboost_log_setup.a...
gcc.compile.c++.pch bin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden/../src/tr1/pch.hpp.gch
In file included from ./boost/cstdfloat.hpp:22,
                 from ./boost/math/tools/test_value.hpp:29,
                 from ./boost/math/special_functions/lambert_w.hpp:64,
                 from ./boost/math/special_functions.hpp:73,
                 from libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/cstdfloat/cstdfloat_limits.hpp:35:13: error: redefinition of ‘class std::numeric_limits<__float128>’
   35 |       class numeric_limits<boost::math::cstdfloat::detail::float_internal128_t>
      |             ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from ./boost/math/special_functions/airy.hpp:10,
                 from ./boost/math/special_functions.hpp:15:
/usr/include/c++/15/limits:2096:12: note: previous definition of ‘class std::numeric_limits<__float128>’
 2096 |     struct numeric_limits<__float128>
      |            ^~~~~~~~~~~~~~~~~~~~~~~~~~

    "g++" -x c++-header -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fvisibility=hidden -DBOOST_ALL_NO_LIB=1 -DBOOST_BUILD_PCH_ENABLED -DNDEBUG -I"." -I"libs/math/src/tr1" -c -o "bin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden/../src/tr1/pch.hpp.gch" "libs/math/build/../src/tr1/pch.hpp"

...failed gcc.compile.c++.pch bin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden/../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_laguerre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_legendre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>beta.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>comp_ellint_1.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>comp_ellint_2.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>comp_ellint_3.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_bessel_i.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_bessel_j.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_bessel_k.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_neumann.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>ellint_1.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>ellint_2.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>ellint_3.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>expint.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>hermite.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>laguerre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>legendre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>riemann_zeta.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>sph_bessel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>sph_legendre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>sph_neumann.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_tr1.a(clean) for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_laguerre.o...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_tr1.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_laguerre.o...
...skipped <pstage/lib>libboost_math_tr1.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_tr1.a...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_laguerref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_legendref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>betaf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>comp_ellint_1f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>comp_ellint_2f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>comp_ellint_3f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_bessel_if.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_bessel_jf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_bessel_kf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_neumannf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>ellint_1f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>ellint_2f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>ellint_3f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>expintf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>hermitef.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>laguerref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>legendref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>riemann_zetaf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>sph_besself.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>sph_legendref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>sph_neumannf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_tr1f.a(clean) for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_laguerref.o...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_tr1f.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_laguerref.o...
...skipped <pstage/lib>libboost_math_tr1f.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_tr1f.a...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_laguerrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_legendrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>betal.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>comp_ellint_1l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>comp_ellint_2l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>comp_ellint_3l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_bessel_il.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_bessel_jl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_bessel_kl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cyl_neumannl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>ellint_1l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>ellint_2l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>ellint_3l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>expintl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>hermitel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>laguerrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>legendrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>riemann_zetal.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>sph_bessell.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>sph_legendrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>sph_neumannl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_tr1l.a(clean) for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_laguerrel.o...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_tr1l.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>assoc_laguerrel.o...
...skipped <pstage/lib>libboost_math_tr1l.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_tr1l.a...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>acosh.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>asinh.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>atanh.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cbrt.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>copysign.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>erfc.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>erf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>expm1.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>fmax.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>fmin.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>fpclassify.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>hypot.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>lgamma.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>llround.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>log1p.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>lround.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>nextafter.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>nexttoward.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>round.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>tgamma.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>trunc.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_c99.a(clean) for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>acosh.o...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_c99.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>acosh.o...
...skipped <pstage/lib>libboost_math_c99.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_c99.a...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>acoshf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>asinhf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>atanhf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cbrtf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>copysignf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>erfcf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>erff.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>expm1f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>fmaxf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>fminf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>fpclassifyf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>hypotf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>lgammaf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>llroundf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>log1pf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>lroundf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>nextafterf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>nexttowardf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>roundf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>tgammaf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>truncf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_c99f.a(clean) for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>acoshf.o...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_c99f.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>acoshf.o...
...skipped <pstage/lib>libboost_math_c99f.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_c99f.a...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>acoshl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>asinhl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>atanhl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>cbrtl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>copysignl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>erfcl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>erfl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>expm1l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>fmaxl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>fminl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>fpclassifyl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>hypotl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>lgammal.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>llroundl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>log1pl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>lroundl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>nextafterl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>nexttowardl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>roundl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>tgammal.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>truncl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_c99l.a(clean) for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>acoshl.o...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_c99l.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>acoshl.o...
...skipped <pstage/lib>libboost_math_c99l.a for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/link-static/threading-multi/visibility-hidden>libboost_math_c99l.a...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/list.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/list.hpp:8,
                 from libs/python/src/list.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/list.o" "libs/python/src/list.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/list.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/long.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/long.hpp:8,
                 from libs/python/src/long.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/long.o" "libs/python/src/long.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/long.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/dict.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/dict.hpp:8,
                 from libs/python/src/dict.cpp:4:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/dict.o" "libs/python/src/dict.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/dict.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/tuple.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/tuple.hpp:8,
                 from libs/python/src/tuple.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/tuple.o" "libs/python/src/tuple.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/tuple.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/str.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/str.hpp:8,
                 from libs/python/src/str.cpp:4:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/str.o" "libs/python/src/str.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/str.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/slice.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/slice.hpp:9,
                 from libs/python/src/slice.cpp:1:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/slice.o" "libs/python/src/slice.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/slice.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/from_python.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/converter/from_python.hpp:8,
                 from libs/python/src/converter/from_python.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/from_python.o" "libs/python/src/converter/from_python.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/from_python.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/registry.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/type_id.hpp:8,
                 from ./boost/python/converter/registry.hpp:7,
                 from libs/python/src/converter/registry.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/registry.o" "libs/python/src/converter/registry.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/registry.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/type_id.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/type_id.hpp:8,
                 from libs/python/src/converter/type_id.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/type_id.o" "libs/python/src/converter/type_id.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/type_id.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/enum.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object_core.hpp:10,
                 from ./boost/python/object/enum_base.hpp:8,
                 from libs/python/src/object/enum.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/enum.o" "libs/python/src/object/enum.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/enum.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/class.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from libs/python/src/object/class.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/class.o" "libs/python/src/object/class.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/class.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/function.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object/function.hpp:8,
                 from ./boost/python/docstring_options.hpp:8,
                 from libs/python/src/object/function.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/function.o" "libs/python/src/object/function.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/function.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/inheritance.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/type_id.hpp:8,
                 from ./boost/python/object/inheritance.hpp:8,
                 from libs/python/src/object/inheritance.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/inheritance.o" "libs/python/src/object/inheritance.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/inheritance.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/life_support.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object/life_support.hpp:7,
                 from libs/python/src/object/life_support.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/life_support.o" "libs/python/src/object/life_support.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/life_support.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/pickle_support.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/make_function.hpp:8,
                 from libs/python/src/object/pickle_support.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/pickle_support.o" "libs/python/src/object/pickle_support.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/pickle_support.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/errors.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/errors.hpp:12,
                 from libs/python/src/errors.cpp:10:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/errors.o" "libs/python/src/errors.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/errors.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/module.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/scope.hpp:8,
                 from libs/python/src/module.cpp:9:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/module.o" "libs/python/src/module.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/module.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/builtin_converters.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/handle.hpp:8,
                 from libs/python/src/converter/builtin_converters.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/builtin_converters.o" "libs/python/src/converter/builtin_converters.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/builtin_converters.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/arg_to_python_base.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/handle.hpp:8,
                 from ./boost/python/converter/arg_to_python_base.hpp:7,
                 from libs/python/src/converter/arg_to_python_base.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/arg_to_python_base.o" "libs/python/src/converter/arg_to_python_base.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/converter/arg_to_python_base.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/iterator.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object_fwd.hpp:8,
                 from ./boost/python/object/iterator_core.hpp:8,
                 from libs/python/src/object/iterator.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/iterator.o" "libs/python/src/object/iterator.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/iterator.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/stl_iterator.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/ssize_t.hpp:9,
                 from ./boost/python/object.hpp:8,
                 from libs/python/src/object/stl_iterator.cpp:10:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/stl_iterator.o" "libs/python/src/object/stl_iterator.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/stl_iterator.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object_protocol.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object_protocol.hpp:8,
                 from libs/python/src/object_protocol.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object_protocol.o" "libs/python/src/object_protocol.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object_protocol.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object_operators.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object_operators.hpp:8,
                 from libs/python/src/object_operators.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object_operators.o" "libs/python/src/object_operators.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object_operators.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/wrapper.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/detail/wrapper_base.hpp:7,
                 from ./boost/python/wrapper.hpp:7,
                 from libs/python/src/wrapper.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/wrapper.o" "libs/python/src/wrapper.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/wrapper.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/import.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/ssize_t.hpp:9,
                 from ./boost/python/object.hpp:8,
                 from ./boost/python/import.hpp:8,
                 from libs/python/src/import.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/import.o" "libs/python/src/import.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/import.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/exec.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/ssize_t.hpp:9,
                 from ./boost/python/object.hpp:8,
                 from ./boost/python/exec.hpp:8,
                 from libs/python/src/exec.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/exec.o" "libs/python/src/exec.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/exec.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/function_doc_signature.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/converter/registrations.hpp:8,
                 from libs/python/src/object/function_doc_signature.cpp:9:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DBOOST_PYTHON_STATIC_LIB -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/function_doc_signature.o" "libs/python/src/object/function_doc_signature.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden/object/function_doc_signature.o...
...skipped <pbin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden>libboost_python313.a(clean) for lack of <pbin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden>list.o...
...skipped <pbin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden>libboost_python313.a for lack of <pbin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden>list.o...
...skipped <pstage/lib>libboost_python313.a for lack of <pbin.v2/libs/python/build/gcc-15.2.0/release/link-static/python-3.13/threading-multi/visibility-hidden>libboost_python313.a...
gcc.compile.c++ bin.v2/libs/thread/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/pthread/thread.o
In file included from /usr/include/pthread.h:33,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr-default.h:35,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr.h:157,
                 from /usr/include/c++/15/ext/atomicity.h:37,
                 from /usr/include/c++/15/bits/ios_base.h:41,
                 from /usr/include/c++/15/ios:46,
                 from /usr/include/c++/15/bits/ostream.h:43,
                 from /usr/include/c++/15/ostream:42,
                 from ./boost/system/error_code.hpp:17,
                 from ./boost/system/system_error.hpp:11,
                 from ./boost/thread/exceptions.hpp:22,
                 from ./boost/thread/pthread/thread_data.hpp:10,
                 from ./boost/thread/thread_only.hpp:17,
                 from libs/thread/src/pthread/thread.cpp:11:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~
In file included from ./boost/functional/hash.hpp:6,
                 from ./boost/thread/detail/thread.hpp:38,
                 from ./boost/thread/thread_only.hpp:22:
./boost/container_hash/hash.hpp:130:33: warning: ‘template<class _Arg, class _Result> struct std::unary_function’ is deprecated [-Wdeprecated-declarations]
  130 |         struct hash_base : std::unary_function<T, std::size_t> {};
      |                                 ^~~~~~~~~~~~~~
In file included from /usr/include/c++/15/string:51,
                 from ./boost/thread/exceptions.hpp:20:
/usr/include/c++/15/bits/stl_function.h:117:12: note: declared here
  117 |     struct unary_function
      |            ^~~~~~~~~~~~~~
In file included from ./boost/concept/assert.hpp:35,
                 from ./boost/concept_check.hpp:20,
                 from ./boost/range/concepts.hpp:19,
                 from ./boost/range/size_type.hpp:20,
                 from ./boost/range/size.hpp:21,
                 from ./boost/range/functions.hpp:20,
                 from ./boost/range/iterator_range_core.hpp:38,
                 from ./boost/algorithm/string/iter_find.hpp:19,
                 from ./boost/algorithm/string/split.hpp:16,
                 from libs/thread/src/pthread/thread.cpp:34:
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::constraint<Model>::failed() [with Model = boost::algorithm::FinderConcept<boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/algorithm/string/iter_find.hpp:77:13:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:47:52: warning: ‘this’ pointer is null [-Wnonnull]
   47 |     static void failed() { ((Model*)0)->constraints(); }
      |                            ~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/algorithm/string/iter_find.hpp:26:
./boost/algorithm/string/concept.hpp:40:18: note: in a call to non-static member function ‘void boost::algorithm::FinderConcept<FinderT, IteratorT>::constraints() [with FinderT = boost::algorithm::detail::token_finderF<boost::algorithm::detail::is_any_ofF<char> >; IteratorT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   40 |             void constraints()
      |                  ^~~~~~~~~~~
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/concept_check.hpp:167:5:   required from ‘struct boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:125:16:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  125 |         struct IncrementableIteratorConcept : CopyConstructible<Iterator>
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
In file included from ./boost/concept_check.hpp:31:
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >]’:
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/iterator/iterator_concepts.hpp:114:7:   [ skipping 18 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’:
./boost/iterator/iterator_concepts.hpp:114:7:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::incrementable_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/range/concepts.hpp:136:13:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/concept_check.hpp:233:5:   required from ‘struct boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >]’:
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:152:13:   [ skipping 17 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’:
./boost/range/concepts.hpp:152:13:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:278:9:   [ skipping 12 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::single_pass_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/range/concepts.hpp:158:13:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:278:9:   [ skipping 12 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/range/concepts.hpp:278:9:   required from ‘struct boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/algorithm/equal.hpp:174:13:   [ skipping 7 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::range_detail::SinglePassIteratorConcept<Iterator>::~SinglePassIteratorConcept() [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:158:13: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  158 |             BOOST_CONCEPT_USAGE(SinglePassIteratorConcept)
      |             ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >]’:
./boost/range/concepts.hpp:284:9:   required from ‘struct boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   required from ‘struct boost::concepts::requirement_<void (*)(boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >)>’
   51 | struct requirement_<void(*)(Model)>
      |        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/algorithm/equal.hpp:174:13:   [ skipping 7 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:16:5: note: in a call to non-static member function ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |     ^
./boost/concept/detail/general.hpp: In instantiation of ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/range/algorithm/equal.hpp:174:13:   required from ‘bool boost::range::equal(const SinglePassRange1&, const SinglePassRange2&) [with SinglePassRange1 = boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; SinglePassRange2 = boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/iterator_range_core.hpp:646:32:   required from ‘bool boost::operator==(const iterator_range<IteratorT>&, const iterator_range<Iterator2T>&) [with Iterator1T = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >; Iterator2T = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
  646 |             return boost::equal( l, r );
      |                    ~~~~~~~~~~~~^~~~~~~~
./boost/algorithm/string/find_iterator.hpp:333:32:   required from ‘bool boost::algorithm::split_iterator<IteratorT>::equal(const boost::algorithm::split_iterator<IteratorT>&) const [with IteratorT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
  333 |                         m_Match==Other.m_Match &&
      |                         ~~~~~~~^~~~~~~~~~~~~~~
./boost/iterator/iterator_facade.hpp:568:26:   required from ‘static bool boost::iterators::iterator_core_access::equal(const Facade1&, const Facade2&, mpl_::true_) [with Facade1 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; Facade2 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; mpl_::true_ = mpl_::bool_<true>]’
  568 |           return f1.equal(f2);
      |                  ~~~~~~~~^~~~
./boost/iterator/iterator_facade.hpp:900:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator==(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; V1 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; TC1 = forward_traversal_tag; Reference1 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >&; Difference1 = long int; Derived2 = boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; V2 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >; TC2 = forward_traversal_tag; Reference2 = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >&; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
./boost/iterator/iterator_adaptor.hpp:305:29:   [ skipping 2 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/general.hpp:39:47: warning: ‘this’ pointer is null [-Wnonnull]
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::SinglePassRangeConcept<T>::~SinglePassRangeConcept() [with T = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:284:9: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  284 |         BOOST_CONCEPT_USAGE(SinglePassRangeConcept)
      |         ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept_check.hpp:167:5:   required from ‘struct boost::CopyConstructible<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:125:16:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  125 |         struct IncrementableIteratorConcept : CopyConstructible<Iterator>
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   [ skipping 15 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::CopyConstructible<TT>::~CopyConstructible() [with TT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:167:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  167 |     BOOST_CONCEPT_USAGE(CopyConstructible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag>]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::incrementable_traversal_tag> >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 19 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::incrementable_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/range/concepts.hpp:136:13:   required from ‘struct boost::range_detail::IncrementableIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::range_detail::IncrementableIteratorConcept<Iterator>::~IncrementableIteratorConcept() [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:136:13: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  136 |             BOOST_CONCEPT_USAGE(IncrementableIteratorConcept)
      |             ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept_check.hpp:233:5:   required from ‘struct boost::EqualityComparable<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/range/concepts.hpp:147:16:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
  147 |         struct SinglePassIteratorConcept
      |                ^~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::EqualityComparable<TT>::~EqualityComparable() [with TT = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:233:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  233 |     BOOST_CONCEPT_USAGE(EqualityComparable) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/concept_check.hpp:208:5:   required from ‘struct boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag>]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::Convertible<boost::iterators::random_access_traversal_tag, boost::iterators::single_pass_traversal_tag> >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 18 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::Convertible<X, Y>::~Convertible() [with X = boost::iterators::random_access_traversal_tag; Y = boost::iterators::single_pass_traversal_tag]’
   30 |       ~model()
      |       ^
./boost/concept_check.hpp:208:5: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  208 |     BOOST_CONCEPT_USAGE(Convertible) {
      |     ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/range/concepts.hpp:158:13:   required from ‘struct boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::range_detail::SinglePassIteratorConcept<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 13 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::range_detail::SinglePassIteratorConcept<Iterator>::~SinglePassIteratorConcept() [with Iterator = __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:158:13: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  158 |             BOOST_CONCEPT_USAGE(SinglePassIteratorConcept)
      |             ^~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp: In instantiation of ‘boost::concepts::usage_requirements<Model>::~usage_requirements() [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’:
./boost/concept/detail/general.hpp:39:47:   required from ‘static void boost::concepts::requirement<boost::concepts::failed************ Model::************>::failed() [with Model = boost::concepts::usage_requirements<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >]’
   39 |     static void failed() { ((Model*)0)->~Model(); }
      |                            ~~~~~~~~~~~~~~~~~~~^~
./boost/range/concepts.hpp:284:9:   required from ‘struct boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >’
   71 |     &::boost::concepts::requirement_<ModelFnPtr>::failed>    \
      |     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:32:62:   required by substitution of ‘template<class Model> boost::concepts::detail::yes boost::concepts::detail::has_constraints_(Model*, wrap_constraints<Model, (& Model::constraints)>*) [with Model = boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > >]’
   32 |   inline yes has_constraints_(Model*, wrap_constraints<Model,&Model::constraints>* = 0);
      |                                                              ^~~~~~~~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:42:5:   required from ‘const bool boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >::value’
   44 |       , value = sizeof( detail::has_constraints_((Model*)0) ) == sizeof(detail::yes) );
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~
./boost/concept/detail/has_constraints.hpp:45:51:   required from ‘struct boost::concepts::not_satisfied<boost::SinglePassRangeConcept<const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > > > >’
   45 |     typedef boost::integral_constant<bool, value> type;
      |                                                   ^~~~
./boost/concept/detail/general.hpp:51:8:   [ skipping 8 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
./boost/iterator/iterator_facade.hpp:901:3:   required from ‘typename boost::iterators::detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<boost::iterators::detail::always_bool2, Derived1, Derived2>::type>::type boost::iterators::operator!=(const iterator_facade<Derived1, V1, TC1, Reference1, Difference1>&, const iterator_facade<Derived2, V2, TC2, Reference2, Difference2>&) [with Derived1 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V1 = std::__cxx11::basic_string<char>; TC1 = forward_traversal_tag; Reference1 = std::__cxx11::basic_string<char>; Difference1 = long int; Derived2 = transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, use_default, use_default>; V2 = std::__cxx11::basic_string<char>; TC2 = forward_traversal_tag; Reference2 = std::__cxx11::basic_string<char>; Difference2 = long int; typename detail::enable_if_interoperable<Derived1, Derived2, typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type>::type = bool; typename boost::mpl::apply2<detail::always_bool2, Derived1, Derived2>::type = bool]’
  885 |       return_prefix iterator_core_access::base_op(                              \
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  886 |           *static_cast<Derived1 const*>(&lhs)                                   \
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  887 |         , *static_cast<Derived2 const*>(&rhs)                                   \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  888 |         , BOOST_ITERATOR_CONVERTIBLE(Derived2,Derived1)                         \
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  889 |       );                                                                        \
      |       ~                                           
/usr/include/c++/15/bits/stl_vector.h:1955:21:   required from ‘void std::vector<_Tp, _Alloc>::_M_range_initialize(_InputIterator, _InputIterator, std::input_iterator_tag) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >]’
 1955 |             for (; __first != __last; ++__first)
      |                    ~~~~~~~~^~~~~~~~~
/usr/include/c++/15/bits/stl_vector.h:751:23:   required from ‘std::vector<_Tp, _Alloc>::vector(_InputIterator, _InputIterator, const allocator_type&) [with _InputIterator = boost::iterators::transform_iterator<boost::algorithm::detail::copy_iterator_rangeF<std::__cxx11::basic_string<char>, __gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::algorithm::split_iterator<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >, boost::iterators::use_default, boost::iterators::use_default>; <template-parameter-2-2> = void; _Tp = std::__cxx11::basic_string<char>; _Alloc = std::allocator<std::__cxx11::basic_string<char> >; allocator_type = std::allocator<std::__cxx11::basic_string<char> >]’
  751 |           _M_range_initialize(__first, __last,
      |           ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
  752 |                               std::__iterator_category(__first));
      |                               ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/algorithm/string/iter_find.hpp:178:31:   required from ‘SequenceSequenceT& boost::algorithm::iter_split(SequenceSequenceT&, RangeT&, FinderT) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; FinderT = detail::token_finderF<detail::is_any_ofF<char> >]’
  178 |             SequenceSequenceT Tmp(itBegin, itEnd);
      |                               ^~~
./boost/algorithm/string/split.hpp:146:50:   required from ‘SequenceSequenceT& boost::algorithm::split(SequenceSequenceT&, RangeT&, PredicateT, token_compress_mode_type) [with SequenceSequenceT = std::vector<std::__cxx11::basic_string<char> >; RangeT = std::__cxx11::basic_string<char>; PredicateT = detail::is_any_ofF<char>]’
  146 |             return ::boost::algorithm::iter_split(
      |                    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
  147 |                 Result,
      |                 ~~~~~~~                           
  148 |                 Input,
      |                 ~~~~~~                            
  149 |                 ::boost::algorithm::token_finder( Pred, eCompress ) );
      |                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
libs/thread/src/pthread/thread.cpp:537:29:   required from here
  537 |                 boost::split(key_val, line, boost::is_any_of(":"));
      |                 ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
./boost/concept/usage.hpp:16:48: warning: ‘this’ pointer is null [-Wnonnull]
   16 |     ~usage_requirements() { ((Model*)0)->~Model(); }
      |                             ~~~~~~~~~~~~~~~~~~~^~
./boost/concept/usage.hpp:30:7: note: in a call to non-static member function ‘boost::SinglePassRangeConcept<T>::~SinglePassRangeConcept() [with T = const boost::iterator_range<__gnu_cxx::__normal_iterator<char*, std::__cxx11::basic_string<char> > >]’
   30 |       ~model()
      |       ^
./boost/range/concepts.hpp:284:9: note: in expansion of macro ‘BOOST_CONCEPT_USAGE’
  284 |         BOOST_CONCEPT_USAGE(SinglePassRangeConcept)
      |         ^~~~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -pedantic -fvisibility=hidden -Wextra -Wno-long-long -Wno-unused-parameter -Wunused-function -pedantic -DBOOST_ALL_NO_LIB=1 -DBOOST_SYSTEM_DYN_LINK=1 -DBOOST_THREAD_BUILD_DLL=1 -DBOOST_THREAD_DONT_USE_CHRONO -DBOOST_THREAD_POSIX -DNDEBUG  -I"." -c -o "bin.v2/libs/thread/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/pthread/thread.o" "libs/thread/src/pthread/thread.cpp"

...failed gcc.compile.c++ bin.v2/libs/thread/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/pthread/thread.o...
...skipped <pbin.v2/libs/thread/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.so.1.69.0 for lack of <pbin.v2/libs/thread/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>pthread/thread.o...
...skipped <pstage/lib>libboost_thread.so.1.69.0 for lack of <pbin.v2/libs/thread/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.so.1.69.0...
...skipped <pstage/lib>libboost_thread.so for lack of <pstage/lib>libboost_thread.so.1.69.0...
gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/posix/stack_traits.o
In file included from ./boost/coroutine/stack_traits.hpp:14,
                 from libs/coroutine/src/posix/stack_traits.cpp:7:
./boost/coroutine/detail/config.hpp:17:4: warning: #warning "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING." [-Wcpp]
   17 | #  warning                  "Boost.Coroutine is now deprecated. Please switch to Boost.Coroutine2. To disable this warning message, define BOOST_COROUTINES_NO_DEPRECATION_WARNING."
      |    ^~~~~~~
In file included from /usr/include/pthread.h:33,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr-default.h:35,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr.h:157,
                 from /usr/include/c++/15/ext/atomicity.h:37,
                 from /usr/include/c++/15/bits/ios_base.h:41,
                 from /usr/include/c++/15/ios:46,
                 from /usr/include/c++/15/bits/ostream.h:43,
                 from /usr/include/c++/15/ostream:42,
                 from ./boost/system/error_code.hpp:17,
                 from ./boost/system/system_error.hpp:11,
                 from ./boost/thread/exceptions.hpp:22,
                 from ./boost/thread/pthread/thread_data.hpp:10,
                 from ./boost/thread/thread_only.hpp:17,
                 from ./boost/thread/thread.hpp:12,
                 from ./boost/thread.hpp:13,
                 from libs/coroutine/src/posix/stack_traits.cpp:22:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~
In file included from ./boost/functional/hash.hpp:6,
                 from ./boost/thread/detail/thread.hpp:38,
                 from ./boost/thread/thread_only.hpp:22:
./boost/container_hash/hash.hpp:130:33: warning: ‘template<class _Arg, class _Result> struct std::unary_function’ is deprecated [-Wdeprecated-declarations]
  130 |         struct hash_base : std::unary_function<T, std::size_t> {};
      |                                 ^~~~~~~~~~~~~~
In file included from /usr/include/c++/15/string:51,
                 from ./boost/thread/exceptions.hpp:20:
/usr/include/c++/15/bits/stl_function.h:117:12: note: declared here
  117 |     struct unary_function
      |            ^~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_CHRONO_DYN_LINK=1 -DBOOST_CONTEXT_DYN_LINK=1 -DBOOST_COROUTINES_DYN_LINK=1 -DBOOST_COROUTINES_SOURCE -DBOOST_DISABLE_ASSERTS -DBOOST_SYSTEM_DYN_LINK=1 -DBOOST_THREAD_BUILD_DLL=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_DLL=1 -DNDEBUG  -I"." -c -o "bin.v2/libs/coroutine/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/posix/stack_traits.o" "libs/coroutine/src/posix/stack_traits.cpp"

...failed gcc.compile.c++ bin.v2/libs/coroutine/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/posix/stack_traits.o...
...skipped <pbin.v2/libs/coroutine/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_coroutine.so.1.69.0 for lack of <pbin.v2/libs/coroutine/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>posix/stack_traits.o...
...skipped <pstage/lib>libboost_coroutine.so.1.69.0 for lack of <pbin.v2/libs/coroutine/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_coroutine.so.1.69.0...
...skipped <pstage/lib>libboost_coroutine.so for lack of <pstage/lib>libboost_coroutine.so.1.69.0...
gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/severity_level.o
In file included from /usr/include/x86_64-linux-gnu/bits/local_lim.h:81,
                 from /usr/include/x86_64-linux-gnu/bits/posix1_lim.h:161,
                 from /usr/include/limits.h:195,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:210,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/syslimits.h:9,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:34,
                 from ./boost/log/detail/config.hpp:33,
                 from libs/log/src/severity_level.cpp:16:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~
In file included from ./boost/functional/hash.hpp:6,
                 from ./boost/thread/detail/thread.hpp:38,
                 from ./boost/thread/thread_only.hpp:22,
                 from ./boost/thread/thread.hpp:12,
                 from libs/log/src/severity_level.cpp:23:
./boost/container_hash/hash.hpp:130:33: warning: ‘template<class _Arg, class _Result> struct std::unary_function’ is deprecated [-Wdeprecated-declarations]
  130 |         struct hash_base : std::unary_function<T, std::size_t> {};
      |                                 ^~~~~~~~~~~~~~
In file included from /usr/include/c++/15/functional:51,
                 from ./boost/config/no_tr1/functional.hpp:21,
                 from ./boost/smart_ptr/intrusive_ptr.hpp:24,
                 from ./boost/log/sources/severity_feature.hpp:20,
                 from libs/log/src/severity_level.cpp:18:
/usr/include/c++/15/bits/stl_function.h:117:12: note: declared here
  117 |     struct unary_function
      |            ^~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fno-strict-aliasing -ftemplate-depth-1024 -DBOOST_ALL_NO_LIB=1 -DBOOST_ATOMIC_DYN_LINK=1 -DBOOST_CHRONO_DYN_LINK=1 -DBOOST_DATE_TIME_DYN_LINK=1 -DBOOST_FILESYSTEM_DYN_LINK=1 -DBOOST_LOG_BUILDING_THE_LIB=1 -DBOOST_LOG_DLL -DBOOST_LOG_HAS_PTHREAD_MUTEX_ROBUST -DBOOST_LOG_USE_AVX2 -DBOOST_LOG_USE_NATIVE_SYSLOG -DBOOST_LOG_USE_SSSE3 -DBOOST_LOG_WITHOUT_DEBUG_OUTPUT -DBOOST_LOG_WITHOUT_EVENT_LOG -DBOOST_SPIRIT_USE_PHOENIX_V3=1 -DBOOST_SYSTEM_DYN_LINK=1 -DBOOST_THREAD_BUILD_DLL=1 -DBOOST_THREAD_DONT_USE_CHRONO=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_DLL=1 -DDATE_TIME_INLINE -DNDEBUG -D_XOPEN_SOURCE=600 -D__STDC_CONSTANT_MACROS  -I"." -I"libs/log/src" -c -o "bin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/severity_level.o" "libs/log/src/severity_level.cpp"

...failed gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/severity_level.o...
gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/event.o
In file included from /usr/include/x86_64-linux-gnu/bits/local_lim.h:81,
                 from /usr/include/x86_64-linux-gnu/bits/posix1_lim.h:161,
                 from /usr/include/limits.h:195,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:210,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/syslimits.h:9,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:34,
                 from ./boost/log/detail/config.hpp:33,
                 from libs/log/src/event.cpp:16:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fno-strict-aliasing -ftemplate-depth-1024 -DBOOST_ALL_NO_LIB=1 -DBOOST_ATOMIC_DYN_LINK=1 -DBOOST_CHRONO_DYN_LINK=1 -DBOOST_DATE_TIME_DYN_LINK=1 -DBOOST_FILESYSTEM_DYN_LINK=1 -DBOOST_LOG_BUILDING_THE_LIB=1 -DBOOST_LOG_DLL -DBOOST_LOG_HAS_PTHREAD_MUTEX_ROBUST -DBOOST_LOG_USE_AVX2 -DBOOST_LOG_USE_NATIVE_SYSLOG -DBOOST_LOG_USE_SSSE3 -DBOOST_LOG_WITHOUT_DEBUG_OUTPUT -DBOOST_LOG_WITHOUT_EVENT_LOG -DBOOST_SPIRIT_USE_PHOENIX_V3=1 -DBOOST_SYSTEM_DYN_LINK=1 -DBOOST_THREAD_BUILD_DLL=1 -DBOOST_THREAD_DONT_USE_CHRONO=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_DLL=1 -DDATE_TIME_INLINE -DNDEBUG -D_XOPEN_SOURCE=600 -D__STDC_CONSTANT_MACROS  -I"." -I"libs/log/src" -c -o "bin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/event.o" "libs/log/src/event.cpp"

...failed gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/event.o...
...skipped <pbin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_log.so.1.69.0 for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>severity_level.o...
...skipped <pstage/lib>libboost_log.so.1.69.0 for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_log.so.1.69.0...
...skipped <pstage/lib>libboost_log.so for lack of <pstage/lib>libboost_log.so.1.69.0...
gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/setup/init_from_settings.o
In file included from /usr/include/x86_64-linux-gnu/bits/local_lim.h:81,
                 from /usr/include/x86_64-linux-gnu/bits/posix1_lim.h:161,
                 from /usr/include/limits.h:195,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:210,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/syslimits.h:9,
                 from /usr/lib/gcc/x86_64-linux-gnu/15/include/limits.h:34,
                 from ./boost/log/detail/config.hpp:33,
                 from ./boost/log/detail/setup_config.hpp:20,
                 from libs/log/src/setup/init_from_settings.cpp:26:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~
In file included from ./boost/functional/hash.hpp:6,
                 from ./boost/thread/detail/thread.hpp:38,
                 from ./boost/thread/thread_only.hpp:22,
                 from ./boost/thread/thread.hpp:12,
                 from ./boost/log/sinks/async_frontend.hpp:39,
                 from ./boost/log/sinks.hpp:25,
                 from libs/log/src/setup/init_from_settings.cpp:54:
./boost/container_hash/hash.hpp:130:33: warning: ‘template<class _Arg, class _Result> struct std::unary_function’ is deprecated [-Wdeprecated-declarations]
  130 |         struct hash_base : std::unary_function<T, std::size_t> {};
      |                                 ^~~~~~~~~~~~~~
In file included from /usr/include/c++/15/string:51,
                 from /usr/include/c++/15/bits/locale_classes.h:42,
                 from /usr/include/c++/15/bits/ios_base.h:43,
                 from /usr/include/c++/15/ios:46,
                 from libs/log/src/setup/init_from_settings.cpp:28:
/usr/include/c++/15/bits/stl_function.h:117:12: note: declared here
  117 |     struct unary_function
      |            ^~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fno-strict-aliasing -ftemplate-depth-1024 -DBOOST_ALL_NO_LIB=1 -DBOOST_ATOMIC_DYN_LINK=1 -DBOOST_CHRONO_DYN_LINK=1 -DBOOST_DATE_TIME_DYN_LINK=1 -DBOOST_FILESYSTEM_DYN_LINK=1 -DBOOST_LOG_DYN_LINK=1 -DBOOST_LOG_HAS_PTHREAD_MUTEX_ROBUST -DBOOST_LOG_SETUP_BUILDING_THE_LIB=1 -DBOOST_LOG_SETUP_DLL -DBOOST_LOG_USE_AVX2 -DBOOST_LOG_USE_NATIVE_SYSLOG -DBOOST_LOG_USE_SSSE3 -DBOOST_LOG_WITHOUT_EVENT_LOG -DBOOST_SPIRIT_USE_PHOENIX_V3=1 -DBOOST_SYSTEM_DYN_LINK=1 -DBOOST_THREAD_BUILD_DLL=1 -DBOOST_THREAD_DONT_USE_CHRONO=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_DLL=1 -DDATE_TIME_INLINE -DNDEBUG -D_XOPEN_SOURCE=600 -D__STDC_CONSTANT_MACROS  -I"." -I"libs/log/src" -c -o "bin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/setup/init_from_settings.o" "libs/log/src/setup/init_from_settings.cpp"

...failed gcc.compile.c++ bin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/setup/init_from_settings.o...
...skipped <pbin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_log_setup.so.1.69.0 for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>setup/init_from_settings.o...
...skipped <pstage/lib>libboost_log_setup.so.1.69.0 for lack of <pbin.v2/libs/log/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_log_setup.so.1.69.0...
...skipped <pstage/lib>libboost_log_setup.so for lack of <pstage/lib>libboost_log_setup.so.1.69.0...
gcc.compile.c++.pch bin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden/../src/tr1/pch.hpp.gch
In file included from ./boost/cstdfloat.hpp:22,
                 from ./boost/math/tools/test_value.hpp:29,
                 from ./boost/math/special_functions/lambert_w.hpp:64,
                 from ./boost/math/special_functions.hpp:73,
                 from libs/math/build/../src/tr1/pch.hpp:9:
./boost/math/cstdfloat/cstdfloat_limits.hpp:35:13: error: redefinition of ‘class std::numeric_limits<__float128>’
   35 |       class numeric_limits<boost::math::cstdfloat::detail::float_internal128_t>
      |             ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from ./boost/math/special_functions/airy.hpp:10,
                 from ./boost/math/special_functions.hpp:15:
/usr/include/c++/15/limits:2096:12: note: previous definition of ‘class std::numeric_limits<__float128>’
 2096 |     struct numeric_limits<__float128>
      |            ^~~~~~~~~~~~~~~~~~~~~~~~~~

    "g++" -x c++-header -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden -fvisibility=hidden -DBOOST_ALL_NO_LIB=1 -DBOOST_BUILD_PCH_ENABLED -DBOOST_MATH_TR1_DYN_LINK=1 -DNDEBUG -I"." -I"libs/math/src/tr1" -c -o "bin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden/../src/tr1/pch.hpp.gch" "libs/math/build/../src/tr1/pch.hpp"

...failed gcc.compile.c++.pch bin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden/../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>assoc_laguerre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>assoc_legendre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>beta.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>comp_ellint_1.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>comp_ellint_2.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>comp_ellint_3.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_bessel_i.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_bessel_j.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_bessel_k.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_neumann.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>ellint_1.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>ellint_2.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>ellint_3.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>expint.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>hermite.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>laguerre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>legendre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>riemann_zeta.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>sph_bessel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>sph_legendre.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>sph_neumann.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_tr1.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>assoc_laguerre.o...
...skipped <pstage/lib>libboost_math_tr1.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_tr1.so.1.69.0...
...skipped <pstage/lib>libboost_math_tr1.so for lack of <pstage/lib>libboost_math_tr1.so.1.69.0...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>assoc_laguerref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>assoc_legendref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>betaf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>comp_ellint_1f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>comp_ellint_2f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>comp_ellint_3f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_bessel_if.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_bessel_jf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_bessel_kf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_neumannf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>ellint_1f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>ellint_2f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>ellint_3f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>expintf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>hermitef.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>laguerref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>legendref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>riemann_zetaf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>sph_besself.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>sph_legendref.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>sph_neumannf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_tr1f.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>assoc_laguerref.o...
...skipped <pstage/lib>libboost_math_tr1f.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_tr1f.so.1.69.0...
...skipped <pstage/lib>libboost_math_tr1f.so for lack of <pstage/lib>libboost_math_tr1f.so.1.69.0...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>assoc_laguerrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>assoc_legendrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>betal.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>comp_ellint_1l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>comp_ellint_2l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>comp_ellint_3l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_bessel_il.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_bessel_jl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_bessel_kl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cyl_neumannl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>ellint_1l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>ellint_2l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>ellint_3l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>expintl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>hermitel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>laguerrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>legendrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>riemann_zetal.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>sph_bessell.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>sph_legendrel.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>sph_neumannl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_tr1l.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>assoc_laguerrel.o...
...skipped <pstage/lib>libboost_math_tr1l.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_tr1l.so.1.69.0...
...skipped <pstage/lib>libboost_math_tr1l.so for lack of <pstage/lib>libboost_math_tr1l.so.1.69.0...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>acosh.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>asinh.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>atanh.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cbrt.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>copysign.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>erfc.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>erf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>expm1.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>fmax.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>fmin.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>fpclassify.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>hypot.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>lgamma.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>llround.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>log1p.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>lround.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>nextafter.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>nexttoward.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>round.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>tgamma.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>trunc.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_c99.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>acosh.o...
...skipped <pstage/lib>libboost_math_c99.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_c99.so.1.69.0...
...skipped <pstage/lib>libboost_math_c99.so for lack of <pstage/lib>libboost_math_c99.so.1.69.0...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>acoshf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>asinhf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>atanhf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cbrtf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>copysignf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>erfcf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>erff.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>expm1f.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>fmaxf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>fminf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>fpclassifyf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>hypotf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>lgammaf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>llroundf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>log1pf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>lroundf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>nextafterf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>nexttowardf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>roundf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>tgammaf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>truncf.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_c99f.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>acoshf.o...
...skipped <pstage/lib>libboost_math_c99f.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_c99f.so.1.69.0...
...skipped <pstage/lib>libboost_math_c99f.so for lack of <pstage/lib>libboost_math_c99f.so.1.69.0...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>acoshl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>asinhl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>atanhl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>cbrtl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>copysignl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>erfcl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>erfl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>expm1l.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>fmaxl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>fminl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>fpclassifyl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>hypotl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>lgammal.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>llroundl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>log1pl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>lroundl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>nextafterl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>nexttowardl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>roundl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>tgammal.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>truncl.o for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>../src/tr1/pch.hpp.gch...
...skipped <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_c99l.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>acoshl.o...
...skipped <pstage/lib>libboost_math_c99l.so.1.69.0 for lack of <pbin.v2/libs/math/build/gcc-15.2.0/release/threading-multi/visibility-hidden>libboost_math_c99l.so.1.69.0...
...skipped <pstage/lib>libboost_math_c99l.so for lack of <pstage/lib>libboost_math_c99l.so.1.69.0...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/list.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/list.hpp:8,
                 from libs/python/src/list.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/list.o" "libs/python/src/list.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/list.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/long.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/long.hpp:8,
                 from libs/python/src/long.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/long.o" "libs/python/src/long.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/long.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/dict.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/dict.hpp:8,
                 from libs/python/src/dict.cpp:4:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/dict.o" "libs/python/src/dict.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/dict.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/tuple.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/tuple.hpp:8,
                 from libs/python/src/tuple.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/tuple.o" "libs/python/src/tuple.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/tuple.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/str.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/str.hpp:8,
                 from libs/python/src/str.cpp:4:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/str.o" "libs/python/src/str.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/str.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/slice.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/slice.hpp:9,
                 from libs/python/src/slice.cpp:1:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/slice.o" "libs/python/src/slice.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/slice.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/from_python.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/converter/from_python.hpp:8,
                 from libs/python/src/converter/from_python.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/from_python.o" "libs/python/src/converter/from_python.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/from_python.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/registry.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/type_id.hpp:8,
                 from ./boost/python/converter/registry.hpp:7,
                 from libs/python/src/converter/registry.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/registry.o" "libs/python/src/converter/registry.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/registry.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/type_id.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/type_id.hpp:8,
                 from libs/python/src/converter/type_id.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/type_id.o" "libs/python/src/converter/type_id.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/type_id.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/enum.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object_core.hpp:10,
                 from ./boost/python/object/enum_base.hpp:8,
                 from libs/python/src/object/enum.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/enum.o" "libs/python/src/object/enum.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/enum.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/class.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from libs/python/src/object/class.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/class.o" "libs/python/src/object/class.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/class.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/function.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object/function.hpp:8,
                 from ./boost/python/docstring_options.hpp:8,
                 from libs/python/src/object/function.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/function.o" "libs/python/src/object/function.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/function.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/inheritance.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/type_id.hpp:8,
                 from ./boost/python/object/inheritance.hpp:8,
                 from libs/python/src/object/inheritance.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/inheritance.o" "libs/python/src/object/inheritance.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/inheritance.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/life_support.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object/life_support.hpp:7,
                 from libs/python/src/object/life_support.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/life_support.o" "libs/python/src/object/life_support.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/life_support.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/pickle_support.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/make_function.hpp:8,
                 from libs/python/src/object/pickle_support.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/pickle_support.o" "libs/python/src/object/pickle_support.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/pickle_support.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/errors.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/errors.hpp:12,
                 from libs/python/src/errors.cpp:10:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/errors.o" "libs/python/src/errors.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/errors.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/module.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/scope.hpp:8,
                 from libs/python/src/module.cpp:9:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/module.o" "libs/python/src/module.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/module.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/builtin_converters.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/handle.hpp:8,
                 from libs/python/src/converter/builtin_converters.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/builtin_converters.o" "libs/python/src/converter/builtin_converters.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/builtin_converters.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/arg_to_python_base.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/handle.hpp:8,
                 from ./boost/python/converter/arg_to_python_base.hpp:7,
                 from libs/python/src/converter/arg_to_python_base.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/arg_to_python_base.o" "libs/python/src/converter/arg_to_python_base.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/converter/arg_to_python_base.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/iterator.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object_fwd.hpp:8,
                 from ./boost/python/object/iterator_core.hpp:8,
                 from libs/python/src/object/iterator.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/iterator.o" "libs/python/src/object/iterator.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/iterator.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/stl_iterator.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/ssize_t.hpp:9,
                 from ./boost/python/object.hpp:8,
                 from libs/python/src/object/stl_iterator.cpp:10:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/stl_iterator.o" "libs/python/src/object/stl_iterator.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/stl_iterator.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object_protocol.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object_protocol.hpp:8,
                 from libs/python/src/object_protocol.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object_protocol.o" "libs/python/src/object_protocol.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object_protocol.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object_operators.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/object_operators.hpp:8,
                 from libs/python/src/object_operators.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object_operators.o" "libs/python/src/object_operators.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object_operators.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/wrapper.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/detail/wrapper_base.hpp:7,
                 from ./boost/python/wrapper.hpp:7,
                 from libs/python/src/wrapper.cpp:5:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/wrapper.o" "libs/python/src/wrapper.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/wrapper.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/import.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/ssize_t.hpp:9,
                 from ./boost/python/object.hpp:8,
                 from ./boost/python/import.hpp:8,
                 from libs/python/src/import.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/import.o" "libs/python/src/import.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/import.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/exec.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/ssize_t.hpp:9,
                 from ./boost/python/object.hpp:8,
                 from ./boost/python/exec.hpp:8,
                 from libs/python/src/exec.cpp:6:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/exec.o" "libs/python/src/exec.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/exec.o...
gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/function_doc_signature.o
In file included from ./boost/python/detail/prefix.hpp:13,
                 from ./boost/python/converter/registrations.hpp:8,
                 from libs/python/src/object/function_doc_signature.cpp:9:
./boost/python/detail/wrap_python.hpp:50:11: fatal error: pyconfig.h: Нет такого файла или каталога
   50 | # include <pyconfig.h>
      |           ^~~~~~~~~~~~
compilation terminated.

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_PYTHON_SOURCE -DNDEBUG  -I"." -I"/usr/include/python3.13" -c -o "bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/function_doc_signature.o" "libs/python/src/object/function_doc_signature.cpp"

...failed gcc.compile.c++ bin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden/object/function_doc_signature.o...
...skipped <pbin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden>libboost_python313.so.1.69.0 for lack of <pbin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden>list.o...
...skipped <pstage/lib>libboost_python313.so.1.69.0 for lack of <pbin.v2/libs/python/build/gcc-15.2.0/release/python-3.13/threading-multi/visibility-hidden>libboost_python313.so.1.69.0...
...skipped <pstage/lib>libboost_python313.so for lack of <pstage/lib>libboost_python313.so.1.69.0...
gcc.compile.c++ bin.v2/libs/type_erasure/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/dynamic_binding.o
In file included from /usr/include/pthread.h:33,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr-default.h:35,
                 from /usr/include/x86_64-linux-gnu/c++/15/bits/gthr.h:157,
                 from /usr/include/c++/15/ext/atomicity.h:37,
                 from /usr/include/c++/15/bits/shared_ptr_base.h:61,
                 from /usr/include/c++/15/bits/shared_ptr.h:53,
                 from /usr/include/c++/15/memory:82,
                 from ./boost/config/no_tr1/memory.hpp:21,
                 from ./boost/get_pointer.hpp:14,
                 from ./boost/bind/mem_fn.hpp:25,
                 from ./boost/mem_fn.hpp:22,
                 from ./boost/bind/bind.hpp:26,
                 from ./boost/bind.hpp:22,
                 from ./boost/thread/pthread/shared_mutex.hpp:12,
                 from ./boost/thread/shared_mutex.hpp:28,
                 from libs/type_erasure/src/dynamic_binding.cpp:14:
./boost/thread/pthread/thread_data.hpp:60:5: error: missing binary operator before token ‘(’
   60 | #if PTHREAD_STACK_MIN > 0
      |     ^~~~~~~~~~~~~~~~~

    "g++"   -fvisibility-inlines-hidden -fPIC -m64 -pthread -O3 -finline-functions -Wno-inline -Wall -fvisibility=hidden  -DBOOST_ALL_NO_LIB=1 -DBOOST_CHRONO_DYN_LINK=1 -DBOOST_SYSTEM_DYN_LINK=1 -DBOOST_THREAD_BUILD_DLL=1 -DBOOST_THREAD_POSIX -DBOOST_THREAD_USE_DLL=1 -DBOOST_TYPE_ERASURE_DYN_LINK -DNDEBUG  -I"." -c -o "bin.v2/libs/type_erasure/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/dynamic_binding.o" "libs/type_erasure/src/dynamic_binding.cpp"

...failed gcc.compile.c++ bin.v2/libs/type_erasure/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden/dynamic_binding.o...
...skipped <pbin.v2/libs/type_erasure/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_type_erasure.so.1.69.0 for lack of <pbin.v2/libs/type_erasure/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>dynamic_binding.o...
...skipped <pstage/lib>libboost_type_erasure.so.1.69.0 for lack of <pbin.v2/libs/type_erasure/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_type_erasure.so.1.69.0...
...skipped <pstage/lib>libboost_type_erasure.so for lack of <pstage/lib>libboost_type_erasure.so.1.69.0...
...skipped <pbin.v2/libs/wave/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_wave.so.1.69.0 for lack of <pbin.v2/libs/thread/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_thread.so.1.69.0...
...skipped <pstage/lib>libboost_wave.so.1.69.0 for lack of <pbin.v2/libs/wave/build/gcc-15.2.0/release/threadapi-pthread/threading-multi/visibility-hidden>libboost_wave.so.1.69.0...
...skipped <pstage/lib>libboost_wave.so for lack of <pstage/lib>libboost_wave.so.1.69.0...
...failed updating 68 targets...
...skipped 327 targets...

