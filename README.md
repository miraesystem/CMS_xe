#레이아웃수정
layouts 에 반응형스킨추가<br>
m.layouts 에 반응형스킨복사형 추가

#위젯수정
widgets/login_info/skins 에 "miraelogin" 스킨추가

#모듈수정
/modules/member/m.skins/default/login_form.html
{getUrl('','act','dispMemberSignUpForm')} -> {getUrl('act','dispMemberSignUpForm')}
현재페이지에서 액션실행하게 수정
