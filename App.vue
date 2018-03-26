var app = new Vue({
    el: '#app',
    data: {
        message: 'Hello, Vue!';
    }
});

var app = new Vue({
            el: '#app',
            data: {
                message: 'Hello, Vue!'
            }
        });

        var app2 = new Vue({
            el: '#app-2',
            data: {
                dynamic: 'I hovered at: ' + new Date().toLocaleString()
            }
        });

        var clickSide = new Vue({
            el: '#click-side',
            data: {
                value: false,
                cows: [
                    "cow1",
                    "cow2",
                    "cow3"
                ]
            },
            methods: {
                changeValue: function () {
                    this.value = !this.value;
                }
            }
        });

    