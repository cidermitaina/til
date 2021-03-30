## やること

- railsチュートリアル7章続き

## やったこと

- railsチュートリアル7章続き
- `redirect_to @user`
    - `redirect_to(@user)`
    - `redirect_to(user_url(@user))`
      - リンクのパスとしてモデルオブジェクトが渡されると自動でidにリンクされる
    - `redirect_to(user_url(@user.id))`
    - `redirect_to("/users/#{@user.id}")` 
