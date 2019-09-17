## Frontend Developer Resume
![My avatar](./Maksim_Sheka.jpg) | Maksim Sheka  
------------ | -------------  
**Contact Info** | Mobile : +375 44 504 53 43; <br>Mail: [sheko.maxim@gmail.com](mailto:sheko.maxim@gmail.com) <br>GitHub: [link](https://github.com/ShekoMaxim)<br>Linkedin: [link](https://www.linkedin.com/in/maxim-sheko-61926bb6/)

## Summary
Full Stack Developer with 3+ years of experience designing, developing, optimizations of the project and internal frameworks. I started developing in 2015.I work with technologies such as react,redux,nodejs and mongodb.I would like to work in IoT.Also I want to learn react native and Node-Red(or Cylon.js)

## Skills

 - JavaScript (jQuery, React, Bootstrap), HTML/CSS, Git, Mocha, Jasmine
 - Waterfall, Agile, Scrum, Kanban
 - Have experience  in responsive, mobile-first development
 - React,Redux,saga,recompose,mobx,material ui,axios,storybook
 - NodeJS, MongoDB and PostgreSQL
 - UI Optimizations,Performance,Code review

## Code examples
Simple react component

     class MessagePopup extends React.PureComponent {  
      render() {  
        const { text, disagree, agree, agreeButtonText, disAgreeButtonText } = this.props;  
      
      return (  
          <Dialog  
      open  
     onClose={this.handleClose}  
            aria-labelledby="alert-dialog-title"  
      aria-describedby="alert-dialog-description"  
      className="popup--outer-wrap"  
      >  
     <div className="popup popup--simple">  
     <DialogContent className="popup__body">  
     <p className="lbl lbl--md txt-b" id="alert-dialog-description">  
      {text}  
                </p>  
     </DialogContent> <DialogActions className="popup__footer">  
     <Button className="btn btn--white btn--square" onClick={agree} color="primary" autoFocus>  
      {agreeButtonText}  
                </Button>  
     <Button className="btn btn--white btn--square" onClick={disagree} color="primary">  
      {disAgreeButtonText}  
                </Button>  
     </DialogActions> </div> </Dialog>  );  
      }  
    }
