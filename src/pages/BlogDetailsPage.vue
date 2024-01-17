<script setup lang="ts">
import {blogs} from "../utils/data";
import {computed} from "vue";
import {useRoute} from "vue-router";

const route =  useRoute()

const blog = computed(() =>{
  return blogs.filter(blog => blog.id === parseInt(<string>route.params.id))[0]
})
</script>

<template>
  <!-- Start Page Title Section -->
  <div class="page-title-area item-bg1">
    <div class="d-table">
      <div class="d-table-cell">
        <div class="container">
          <div class="page-title-content">
            <h2>{{blog.title}}</h2>
            <ul>
              <li>  <router-link to="/">Home</router-link>
              </li>
              <li>Blog Details</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- End Page Title Section -->

  <!-- Start Blog Details Section -->
  <section class="blog-details-area ptb-100">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-md-12">
          <div class="blog-details-desc">
            <div class="article-image">
              <img :src="`/assets/img/blog-${blog.id}.jpg`" alt="image">
            </div>
            <div class="article-content">
              <div class="entry-meta">
                <ul>
                  <li> <span>Posted On:</span>  <a href="#">{{blog.date}}</a></li>
                  <li> <span>Posted By:</span>  <a href="#">{{blog.author}}</a></li>
                </ul>
              </div>
              <h3>{{ blog.title }}</h3>
              <p>{{blog.content}}</p>
              <ul class="wp-block-gallery columns-2">
                <li class="blocks-gallery-item">
                  <figure>
                    <img src="/assets/img/blog-2.jpg" alt="image">
                  </figure>
                </li>
                <li class="blocks-gallery-item">
                  <figure>
                    <img src="/assets/img/blog-3.jpg" alt="image">
                  </figure>
                </li>
              </ul>

              <p>{{blog.body}}</p>
            </div>
            <div class="article-footer">
              <div class="article-tags"> <span>Tag:</span>
                <a href="#">Solutions</a>
                <a href="#">Guide</a>
              </div>
              <div class="article-share">
                <ul class="social">
                  <li><span>Share:</span></li>
                  <li><a href="#"> <i class="fab fa-facebook-f"></i></a></li>
                  <li><a href="#"> <i class="fab fa-twitter"></i></a></li>
                  <li><a href="#"> <i class="fab fa-instagram"></i></a></li>
                </ul>
              </div>
            </div>
            <div class="post-navigation">
              <div class="navigation-links">
                <div class="nav-previous">
                  <a href="#"><i class="fa fa-arrow-left"></i> Prev Post</a>
                </div>
                <div class="nav-next">
                  <a href="#">Next Post <i class="fa fa-arrow-right"></i></a>
                </div>
              </div>
            </div>
            <div class="comments-area">
              <h3 class="comments-title">3 Comments:</h3>
              <ol class="comment-list">
                <li class="comment">
                  <article class="comment-body">
                    <footer class="comment-meta">
                      <div class="comment-author vcard">
                        <img src="/assets/img/blog-1.jpg" class="avatar" alt="image"> <b class="fn">Wilson Swanson</b>
                        <span class="says">says:</span>
                      </div>
                      <div class="comment-metadata">
                        <a href="#">
                          <span>June 15 - 2024 12:30 PM</span>
                        </a>
                      </div>
                    </footer>
                    <div class="comment-content">
                      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. enim ad minim veniam, quis nostrud exercitation.</p>
                    </div>
                    <div class="reply"> <a href="#" class="comment-reply-link">Reply</a>
                    </div>
                  </article>
                  <ol class="children">
                    <li class="comment">
                      <article class="comment-body">
                        <footer class="comment-meta">
                          <div class="comment-author vcard">
                            <img src="/assets/img/blog-2.jpg" class="avatar" alt="image"> <b class="fn">Ella Hodges</b>
                            <span class="says">says:</span>
                          </div>
                          <div class="comment-metadata">
                            <a href="#">
                              <span>June 15 - 2024 12:30 PM</span>
                            </a>
                          </div>
                        </footer>
                        <div class="comment-content">
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. enim ad minim veniam, quis nostrud exercitation.</p>
                        </div>
                        <div class="reply"> <a href="#" class="comment-reply-link">Reply</a>
                        </div>
                      </article>
                    </li>
                  </ol>
                </li>
                <li class="comment">
                  <article class="comment-body">
                    <footer class="comment-meta">
                      <div class="comment-author vcard">
                        <img src="/assets/img/team-4.jpg" class="avatar" alt="image"> <b class="fn">Melissa Bryant</b>
                        <span class="says">says:</span>
                      </div>
                      <div class="comment-metadata">
                        <a href="#">
                          <span>June 15 - 2024 12:30 PM</span>
                        </a>
                      </div>
                    </footer>
                    <div class="comment-content">
                      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. enim ad minim veniam, quis nostrud exercitation.</p>
                    </div>
                    <div class="reply"><a href="#" class="comment-reply-link">Reply</a></div>
                  </article>
                </li>
              </ol>
              <div class="comment-respond">
                <h3 class="comment-reply-title">Leave a Reply</h3>
                <form class="comment-form">
                  <p class="comment-notes"> <span id="email-notes">Your email address will not be published.</span>
                    Required fields are marked <span class="required">*</span>
                  </p>
                  <p class="comment-form-comment">
                    <label>Comment</label>
                    <textarea name="comment" id="comment" cols="45" rows="5" maxlength="65525" required></textarea>
                  </p>
                  <p class="comment-form-author">
                    <label>Name <span class="required">*</span>
                    </label>
                    <input type="text" id="author" name="author" required>
                  </p>
                  <p class="comment-form-email">
                    <label>Email <span class="required">*</span>
                    </label>
                    <input type="email" id="email" name="email" required>
                  </p>
                  <p class="comment-form-url">
                    <label>Website</label>
                    <input type="url" id="url" name="url">
                  </p>
                  <p class="comment-form-cookies-consent">
                    <input type="checkbox" value="yes" name="wp-comment-cookies-consent" id="wp-comment-cookies-consent">
                    <label for="wp-comment-cookies-consent">Save my name, email, and website in this browser for the next time I comment.</label>
                  </p>
                  <p class="form-submit">
                    <input type="submit" name="submit" id="submit" class="submit" value="Post Comment">
                  </p>
                </form>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-12">
          <aside class="widget-area" id="secondary">
            <section class="widget widget_search">
              <form class="search-form search-top">
                <label>
                  <input type="search" class="search-field" placeholder="Search...">
                </label>
                <button type="submit"> <i class="fas fa-search"></i></button>
              </form>
            </section>
            <section class="widget widget_techvio_posts_thumb">
              <h3 class="widget-title">Popular Posts</h3>
              <article class="item">
                <a href="#" class="thumb">
                  <img src="/assets/img/blog-1.jpg" alt="image">
                </a>
                <div class="info">
                  <span>June 10, 2024</span>
                  <h4 class="title usmall">
                    <a href="#">Planning for a Safe Return to the Workplace IT Solutions</a>
                  </h4>
                </div>
              </article>
              <article class="item">
                <a href="#" class="thumb">
                  <img src="/assets/img/blog-2.jpg" alt="image">
                </a>
                <div class="info">
                  <span>June 15, 2024</span>
                  <h4 class="title usmall">
                    <a href="#">Announcing Our New Smiles for Success Charity</a>
                  </h4>
                </div>
              </article>
              <article class="item">
                <a href="#" class="thumb">
                  <img src="/assets/img/blog-3.jpg" alt="image">
                </a>
                <div class="info">
                  <span>June 25, 2024</span>
                  <h4 class="title usmall">
                    <a href="#">Machine Learning Applications for Every Industry</a>
                  </h4>
                </div>
              </article>
            </section>
            <section class="widget widget_categories">
              <h3 class="widget-title">Categories</h3>
              <ul>
                <li><a href="#">Business <span class="categories-link-count"> (33)</span></a></li>
                <li><a href="#">Solutions <span class="categories-link-count"> (45)</span></a></li>
                <li><a href="#">Technology <span class="categories-link-count"> (20)</span></a></li>
                <li><a href="#">Digital Marketing <span class="categories-link-count"> (15)</span></a></li>
                <li><a href="#">Graphic Design <span class="categories-link-count"> (7)</span></a></li>
              </ul>
            </section>
            <section class="widget widget_tag_cloud">
              <h3 class="widget-title">Tags</h3>
              <div class="tagcloud">
                <a href="#">Web Design</a>
                <a href="#">Responsive</a>
                <a href="#">Applications</a>
                <a href="#">Solutions</a>
                <a href="#">Industry</a>
                <a href="#">Marketing</a>
                <a href="#">Development</a>
                <a href="#">Startup</a>
                <a href="#">Graphic Design</a>
                <a href="#">SEO</a>
                <a href="#">Data Security</a>
              </div>
            </section>
          </aside>
        </div>
      </div>
    </div>
  </section>
  <!-- End Blog Details Section -->

</template>

<style scoped>

</style>
