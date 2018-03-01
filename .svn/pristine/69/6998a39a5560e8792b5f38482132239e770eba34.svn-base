
var open=require('../controllers/openController');

/*开放路径*/
exports.route=function(app){
    //得到其他平台的免登录地址（用户）
    app.post('/open/getLoginChat4Url',open.getLoginChat4Url);
    //得到其他平台的免登录地址（管理员）
    app.post('/open/getAdminLoginChat4Url',open.getAdminLoginChat4Url);
}