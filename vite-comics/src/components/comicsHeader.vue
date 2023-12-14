
<script>
export default {
    
}
</script>

<template lang="">
    <header>
        <section class='container'>
            <div class='logo'>
                <img src="../assets/img/dc-logo.png" alt="DC's logo">
            </div>
            <nav>
                <ul>
                    <li>
                        Characters
                    </li>
                    <li>
                        Characters
                    </li>
                    <li>
                        Characters
                    </li>
                    <li>
                        Characters
                    </li>
                    <li>
                        Characters
                    </li>
                </ul>
            </nav>
        </section>

    </header>
</template>

<style lang="scss" scoped>
    @use '../styles/variables' as *;
    @use '../styles/mixins' as *;

    header{
        height: 100px;
        background-color: red;
            .container{
                width: 70%;
                height: 100%;
                background-color: aqua;
                margin: 0 auto;
                @include flex(row, space-between, center);
            }

            div.logo{
                width: 100%;
                height: 100%;
            }

            div.logo img{
                height: 100%;
                padding: 1rem;
            }

          nav{
            

            ul{
                list-style-type: none;
                
                li{
                    
                }
            }
          }
    }


</style>